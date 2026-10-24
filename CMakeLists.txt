cmake_minimum_required(VERSION 3.15)
project(GPU_Secp256k1_Batch)

set(CMAKE_CXX_STANDARD 17)

# Compute API integration pending
# find_package(DirectX REQUIRED)

add_executable(gpu_batch_verify src/main.cpp src/compute_pipeline.cpp)
# target_link_libraries(gpu_batch_verify DirectX::D3D12)
