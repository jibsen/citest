project('citest', 'c',
  meson_version : '>=0.60.0',
  default_options : [
    'b_ndebug=if-release',
    'c_std=c99',
    'default_library=static',
    'warning_level=3',
  ],
  version : '0.1.0',
  license : 'MIT'
)

e = executable('citest', 'citest.c')

test('test CI', e)
