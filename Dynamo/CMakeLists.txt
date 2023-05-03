cmake_minimum_required(VERSION 3.13...3.16 FATAL_ERROR)
project(Dynamo VERSION 0.0.1 LANGUAGES CXX)

add_executable(Dynamo src/main.cpp)
target_compile_features(Dynamo PRIVATE cxx_auto_type)

# find_package(JSONUtils 1.0 REQUIRED)
# target_link_libraries(example_exec JSONUtils::JSONUtils)
