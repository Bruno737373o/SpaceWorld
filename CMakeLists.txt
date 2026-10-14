cmake_minimum_required(VERSION 3.10)
project(SpaceWorld C CXX)

set(CMAKE_CXX_STANDARD 17)

# Inclui todos os arquivos fonte .cpp e .c da pasta do seu código
file(GLOB_RECURSE SOURCES "src/*.cpp" "src/*.c" "*.cpp" "*.c")

add_executable(SpaceWorld ${SOURCES})
