
cmake_minimum_required (VERSION 3.8)


find_package(Eigen3 CONFIG REQUIRED)

add_executable(QrDecomposition QrDecomposition.cpp)
target_link_libraries(QrDecomposition PRIVATE Eigen3::Eigen)