#
project(FFMPEG_Learn)

cmake_minimum_required(VERSION 3.10)

SET (CMAKE_MODULE_PATH "${PROJECT_SOURCE_DIR}/build/CMakeModules/;${CMAKE_MODULE_PATH}")

set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/../lib)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/../lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/../bin)

INCLUDE (globalsetting)

add_subdirectory(01ffmpeg_learn)
add_subdirectory(02ffmpeg_learn)
