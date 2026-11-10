add_subdirectory(SDL)

add_library(vendor PRIVATE)
target_link_libraries(vendor PRIVATE SDL3::SDL3)