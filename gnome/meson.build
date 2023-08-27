schemas = [
  'org.gnome.desktop.interface.gschema.override',
  'org.gnome.gedit.preferences.editor.gschema.override',
]

custom_target('90_budgie_gnome_settings.gschema.override',
    capture: true,
    command: ['cat', '@INPUT@'],
    input: schemas,
    install_dir: path_schema,
    install: true,
    output: '90_budgie_gnome_settings.gschema.override',
)