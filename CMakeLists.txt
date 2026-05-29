cmake_minimum_required(VERSION 3.23)
project(RayCasting)

set(CMAKE_CXX_STANDARD 20)


add_subdirectory(lib)

add_executable(RayCasting main.cpp)

target_link_libraries(RayCasting ${SDL2_LIBRARIES} SDL2_gfx GuiLib)


