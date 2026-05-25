cmake_minimum_required(VERSION 3.25)

project(XDBot2)

find_package(Geode REQUIRED)

add_geode_mod(
    ${PROJECT_NAME}
    GD_VERSION 2.2074
    SDK_VERSION 3.0.0-beta.1
)

target_sources(${PROJECT_NAME} PRIVATE src/main.cpp)
