# CMake entry point
cmake_minimum_required (VERSION 2.6)
project (finanApp)

include_directories(
  external/termcolor/include/
)

add_executable( finanApp
src/program.cpp
src/input.cpp
src/input.h
src/output.cpp
src/output.h
src/summary.cpp
src/summary.h
src/commands.h
src/commandHandler.cpp
src/commandHandler.h
src/filehandler.cpp
src/filehandler.h
)
