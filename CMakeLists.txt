# WMM interface library build.
add_library(WMM INTERFACE)
target_sources(WMM INTERFACE ${CMAKE_CURRENT_LIST_DIR}/src/WMM.cpp)
target_include_directories(WMM INTERFACE ${CMAKE_CURRENT_LIST_DIR}/include/)