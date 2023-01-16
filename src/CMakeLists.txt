project(MakeWindow)

add_library(Window Window.cpp)
target_include_directories(Window
    PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/../include)
