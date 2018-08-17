cmake_minimum_required(VERSION 2.8)
project(test_library)
find_package(Boost REQUIRED)
add_definitions( -std=c++11 )
include_directories( ${Boost_INCLUDE_DIR} )
add_executable(test_library ./test_root_finding.cpp)
target_link_libraries(test_library ${Boost_LIBRARIES})

