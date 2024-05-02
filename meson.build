project('ght', 'c',
    default_options: [
      'werror=true',
      'warning_level=2'
  ]
)

ght_src = files('src/ght.c')
ght_include = include_directories('include/')

libght = library('ght', ght_src, include_directories: ght_include)

