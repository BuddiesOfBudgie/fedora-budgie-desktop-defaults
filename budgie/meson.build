schemas = [
  'com.solus-project.budgie-menu.gschema.override',
  'com.solus-project.icon-tasklist.gschema.override',
  'org.buddiesofbudgie.budgie-desktop-view.gschema.override',
]

custom_target('10_budgie_org_settings.gschema.override',
    capture: true,
    command: ['cat', '@INPUT@'],
    input: schemas,
    install_dir: path_schema,
    install: true,
    output: '10_budgie_org_settings.gschema.override',
)