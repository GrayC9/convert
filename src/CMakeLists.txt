
add_library(convert_lib
    convert_func.cpp
)

add_executable(convert
    convert_func.cpp
    convert_main.cpp
)

target_include_directories(convert_lib
    PRIVATE
        ${CMAKE_CURRENT_SOURCE_DIR}/
    PUBLIC
        $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/>
)