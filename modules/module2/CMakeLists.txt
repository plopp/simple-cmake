add_library(module2 OBJECT src/module2.cpp)

set_target_properties(module2 PROPERTIES
	LINKER_LANGUAGE CXX)

target_include_directories(module2 PUBLIC
	$<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include/>)
