project(MakeWindow)

add_executable(MakeWindow MakeWindow.cpp)

target_link_libraries(MakeWindow
    PRIVATE
    Window)
