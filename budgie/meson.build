schemas = [
  'com.solus-project.budgie-menu.gschema.override',
  'com.solus-project.icon-tasklist.gschema.override',
  'org.buddiesofbudgie.budgie-desktop-view.gschema.override',
]

custom_target('90_budgie_settings.gschema.override',
    capture: true,
    command: ['cat', '@INPUT@'],
    input: schemas,
    install_dir: path_schema,
    install: true,
    output: '90_budgie_settings.gschema.override',
)