target_sources(
  mlx
  PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/allocator.cpp
          ${CMAKE_CURRENT_SOURCE_DIR}/event.cpp
          ${CMAKE_CURRENT_SOURCE_DIR}/fence.cpp
          ${CMAKE_CURRENT_SOURCE_DIR}/eval.cpp
          ${CMAKE_CURRENT_SOURCE_DIR}/primitives.cpp)
