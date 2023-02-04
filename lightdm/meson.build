schemas = [
  'x.dm.slick-greeter.gschema.override',
]

custom_target('10_budgie_lightdm.gschema.override',
    capture: true,
    command: ['cat', '@INPUT@'],
    input: schemas,
    install_dir: path_schema,
    install: true,
    output: '10_budgie_lightdm.gschema.override',
)