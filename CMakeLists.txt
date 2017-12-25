file(GLOB_RECURSE SOURCES_CC ./udt4/src/*.cpp)
add_library(udt4 STATIC ${SOURCES_CC})
