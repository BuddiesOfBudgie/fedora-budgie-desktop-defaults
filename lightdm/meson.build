schemas = [
  'x.dm.slick-greeter.gschema.override',
]

custom_target('90_budgie_lightdm.gschema.override',
    capture: true,
    command: ['cat', '@INPUT@'],
    input: schemas,
    install_dir: path_schema,
    install: true,
    output: '90_budgie_lightdm.gschema.override',
)