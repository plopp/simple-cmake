add_library(module1 OBJECT src/module1.cpp)

set_target_properties(module1 PROPERTIES
	LINKER_LANGUAGE CXX)

target_include_directories(module1 PUBLIC
	$<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include/>)
