project(
  'budgie-desktop-defaults',
  'c',
  version: '0.5',
  license: [
    'CC-BY-SA-4.0'
  ],
  default_options : [
    'warning_level=3'
  ]
)

path_prefix = get_option('prefix')
path_data = join_paths(path_prefix, get_option('datadir'))
path_schema = join_paths(path_data, 'glib-2.0', 'schemas')

subdir('budgie')
subdir('gnome')
subdir('lightdm')

report = [
    '    Build configuration:',
    '    ====================',
    '',
    '    prefix:                                @0@'.format(path_prefix),
    '    datadir:                               @0@'.format(path_data),
    '    schema dir:                            @0@'.format(path_schema),
]

message('\n\n\n' + '\n'.join(report) + '\n\n')