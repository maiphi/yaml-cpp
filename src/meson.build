
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
  install : false)

yaml_dep = declare_dependency(
  include_directories : include_dir,
  link_with : yaml)
