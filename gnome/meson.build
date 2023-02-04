schemas = [
  'org.gnome.desktop.background.gschema.override',
  'org.gnome.desktop.interface.gschema.override',
  'org.gnome.desktop.screensaver.gschema.override',
]

custom_target('10_budgie_gnome_settings.gschema.override',
    capture: true,
    command: ['cat', '@INPUT@'],
    input: schemas,
    install_dir: path_schema,
    install: true,
    output: '10_budgie_gnome_settings.gschema.override',
)