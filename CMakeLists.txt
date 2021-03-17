cmake_minimum_required(VERSION 3.16.0)
set (CMAKE_CXX_STANDARD 11)
set (CMAKE_BUILD_TYPE Debug)
set (EXECUTABLE_OUTPUT_PATH "..")

# Project name
project(cpp_template)

set(SOURCE_DIR src)
set(INCLUDE_DIR include)

set(HEADER_FILES

)

set(SOURCE_FILES
    ${SOURCE_DIR}/main.cpp
  
)

# Executable name
add_executable(cpp_template ${DOMAINS_SOURCE_FILES}
    ${SOURCE_FILES}
)

target_include_directories(cpp_template PUBLIC ${INCLUDE_DIR})