project(trash)
add_executable(trash example.cpp)
target_link_directories(trash PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
target_link_libraries(trash zlibd zlibstaticd)
