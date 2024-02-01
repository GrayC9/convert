
add_library(convert_lib convert_func.cpp convert_main.cpp)


target_include_directories(convert_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
