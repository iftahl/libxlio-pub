# Variables
# check maybe need AM_CPPFLAGS := -I$(top_srcdir)/src

#AM_CPPFLAGS = -I$(top_srcdir)/src/core/util/yaml-cpp/include

noinst_LTLIBRARIES = libyaml-cpp.la
libyaml_cpp_la_LDFLAGS = -static
libyaml_cpp_la_LIBADD = -lrt
libyaml_cpp_la_SOURCES = \
    src/binary.cpp \
    src/collectionstack.h \
    src/convert.cpp \
    src/depthguard.cpp \
    src/directives.cpp \
    src/directives.h \
    src/emit.cpp \
    src/emitfromevents.cpp \
    src/emitter.cpp \
    src/emitterstate.cpp \
    src/emitterstate.h \
    src/emitterutils.cpp \
    src/emitterutils.h \
    src/exceptions.cpp \
    src/exp.cpp \
    src/exp.h \
    src/fptostring.cpp \
    src/indentation.h \
    src/memory.cpp \
    src/nodebuilder.cpp \
    src/nodebuilder.h \
    src/node.cpp \
    src/node_data.cpp \
    src/nodeevents.cpp \
    src/nodeevents.h \
    src/null.cpp \
    src/ostream_wrapper.cpp \
    src/parse.cpp \
    src/parser.cpp \
    src/ptr_vector.h \
    src/regeximpl.h \
    src/regex_yaml.cpp \
    src/regex_yaml.h \
    src/scanner.cpp \
    src/scanner.h \
    src/scanscalar.cpp \
    src/scanscalar.h \
    src/scantag.cpp \
    src/scantag.h \
    src/scantoken.cpp \
    src/setting.h \
    src/simplekey.cpp \
    src/singledocparser.cpp \
    src/singledocparser.h \
    src/streamcharsource.h \
    src/stream.cpp \
    src/stream.h \
    src/stringsource.h \
    src/tag.cpp \
    src/tag.h \
    src/token.h

libyaml_cpp_la_SOURCES += \
    src/contrib/dragonbox.h \
    src/contrib/graphbuilderadapter.cpp \
    src/contrib/graphbuilderadapter.h \
    src/contrib/graphbuilder.cpp \
    src/contrib/yaml-cpp.natvis \
    src/contrib/yaml-cpp.natvis.md

# Include headers (non-installed headers used internally by yaml-cpp)
nodist_include_HEADERS = \
    include/anchor.h \
    include/binary.h \
    include/depthguard.h \
    include/dll.h \
    include/emitfromevents.h \
    include/emitterdef.h \
    include/emitter.h \
    include/emittermanip.h \
    include/emitterstyle.h \
    include/eventhandler.h \
    include/exceptions.h \
    include/fptostring.h \
    include/mark.h \
    include/noexcept.h \
    include/null.h \
    include/ostream_wrapper.h \
    include/parser.h \
    include/stlemitter.h \
    include/traits.h \
    include/yaml.h


nodist_include_HEADERS += \
    include/node/convert.h \
    include/node/emit.h \
    include/node/impl.h \
    include/node/iterator.h \
    include/node/node.h \
    include/node/parse.h \
    include/node/ptr.h \
    include/node/type.h

nodist_include_HEADERS += \
    include/node/detail/impl.h \
    include/node/detail/iterator_fwd.h \
    include/node/detail/iterator.h \
    include/node/detail/memory.h \
    include/node/detail/node_data.h \
    include/node/detail/node.h \
    include/node/detail/node_iterator.h \
    include/node/detail/node_ref.h

nodist_include_HEADERS += \
    include/contrib/anchordict.h \
    include/contrib/graphbuilder.h


# Include directory for yaml-cpp headers
AM_CPPFLAGS = -I$(srcdir)/include


