add_library(Projection projection.cpp)

find_package(Eigen3 3.3 REQUIRED NO_MODULE)

target_link_libraries(Projection Eigen3::Eigen)
target_include_directories(Projection PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})