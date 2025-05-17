cmake_minimum_required(VERSION 3.10)

project(hello)

# add_executable(${PROJECT_NAME} ./main.c)

# install(TARGETS ${PROJECT_NAME} RUNTIME DESTINATION ${PROJECT_SOURCE_DIR})

add_library(${CMAKE_PROJECT_NAME} SHARED
        # List C/C++ source files with relative paths to this CMakeLists.txt.
        main.c)

# Specifies libraries CMake should link to your target library. You
# can link libraries from various origins, such as libraries defined in this
# build script, prebuilt third-party libraries, or Android system libraries.
target_link_libraries(${CMAKE_PROJECT_NAME}
        # List libraries link to the target library
        android
        log)