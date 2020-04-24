add_library(libB src/B.cpp)
target_include_directories(libB PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)
