
# A minimal Meson build system for yaml-cpp.
# Can be used to include yaml-cpp as a Meson subproject.
# Generates a (per default static) library. Doesn't install anything.

project(
  'yaml-cpp',
  'cpp',
  version : '0.6.3',
  license : 'MIT',
  default_options : [
    'cpp_std=c++11',
    'buildtype=release',
    'warning_level=3',
    'default_library=static'])

if get_option('arch') != ''
  add_project_arguments('-march=' + get_option('arch'), language : 'cpp')
endif

include_dir = include_directories('include')

subdir('src')
