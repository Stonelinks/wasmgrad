add_executable(engine_example engine_example.cpp)
target_link_libraries(engine_example wasmgrad fmt::fmt)

add_executable(mlp_example mlp_example.cpp)
target_link_libraries(mlp_example wasmgrad fmt::fmt)
