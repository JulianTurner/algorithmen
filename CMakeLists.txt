cmake_minimum_required(VERSION 3.22.1)
project(algorithmenUndDatenstrukturen LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)

add_subdirectory(0_Playground)
add_subdirectory(1_Fundamentale_Datenstrukturen)
add_subdirectory(2_Fundamentale_Algorithmen)
add_subdirectory(3_Reale_Problemstellungen)
add_subdirectory(4_Ausblick)
