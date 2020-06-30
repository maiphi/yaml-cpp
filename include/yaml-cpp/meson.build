
headers = [
  'anchor.h',
  'binary.h',
  'depthguard.h',
  'dll.h',
  'emitfromevents.h',
  'emitter.h',
  'emitterdef.h',
  'emittermanip.h',
  'emitterstyle.h',
  'eventhandler.h',
  'exceptions.h',
  'mark.h',
  'null.h',
  'ostream_wrapper.h',
  'parser.h',
  'stlemitter.h',
  'traits.h',
  'yaml.h']

headers_contrib = [
  'contrib/anchordict.h',
  'contrib/graphbuilder.h']

headers_node = [
  'node/convert.h',
  'node/emit.h',
  'node/impl.h',
  'node/iterator.h',
  'node/node.h',
  'node/parse.h',
  'node/ptr.h',
  'node/type.h']

headers_node_detail = [
  'node/detail/impl.h',
  'node/detail/iterator_fwd.h',
  'node/detail/iterator.h',
  'node/detail/memory.h',
  'node/detail/node_data.h',
  'node/detail/node_iterator.h',
  'node/detail/node_ref.h',
  'node/detail/node.h']

install_headers(headers, subdir : 'yaml-cpp')
install_headers(headers_contrib, subdir : 'yaml-cpp/contrib')
install_headers(headers_node, subdir : 'yaml-cpp/node')
install_headers(headers_node_detail, subdir : 'yaml-cpp/node/detail')
