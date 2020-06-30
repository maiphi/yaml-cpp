
src = [
  'binary.cpp',
  'convert.cpp',
  'depthguard.cpp',
  'directives.cpp',
  'emit.cpp',
  'emitfromevents.cpp',
  'emitter.cpp',
  'emitterstate.cpp',
  'emitterutils.cpp',
  'exceptions.cpp',
  'exp.cpp',
  'memory.cpp',
  'nodebuilder.cpp',
  'node.cpp',
  'node_data.cpp',
  'nodeevents.cpp',
  'null.cpp',
  'ostream_wrapper.cpp',
  'parse.cpp',
  'parser.cpp',
  'regex_yaml.cpp',
  'scanner.cpp',
  'scanscalar.cpp',
  'scantag.cpp',
  'scantoken.cpp',
  'simplekey.cpp',
  'singledocparser.cpp',
  'stream.cpp',
  'tag.cpp',
  'contrib/graphbuilder.cpp',
  'contrib/graphbuilderadapter.cpp']

yaml = library(
  'yaml-cpp',
  src,
  include_directories : include_dir,
  install : true)

pkg = import('pkgconfig')
pkg.generate(
  yaml,
  filebase : 'yaml-cpp',
  name : 'Yaml-cpp',
  description : 'A YAML parser and emitter for C++')

yaml_dep = declare_dependency(
  include_directories : include_dir,
  link_with : yaml)

if meson.version().version_compare('>=0.54.0')
  meson.override_dependency('yaml-cpp', yaml_dep)
endif
