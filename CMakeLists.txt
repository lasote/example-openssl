PROJECT(ExampleOpenSSL)
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

INCLUDE(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
CONAN_BASIC_SETUP()

ADD_EXECUTABLE(md5 main.cpp)
TARGET_LINK_LIBRARIES(md5 ${CONAN_LIBS})
