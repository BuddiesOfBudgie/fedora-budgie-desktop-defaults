schemas = [
  'org.gnome.desktop.interface.gschema.override',
  'org.gnome.gedit.preferences.editor.gschema.override',
]

custom_target('10_budgie_org_gnome_settings.gschema.override',
    capture: true,
    command: ['cat', '@INPUT@'],
    input: schemas,
    install_dir: path_schema,
    install: true,
    output: '10_budgie_org_gnome_settings.gschema.override',
)