file(GLOB_RECURSE ALL_CUDA_SOURCE_FILES "*.cu")
cuda_add_library(cupoch_planning ${ALL_CUDA_SOURCE_FILES})
target_link_libraries(cupoch_planning cupoch_collision)