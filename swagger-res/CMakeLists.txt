add_custom_target(copy-runtime-files ALL
    COMMAND ${CMAKE_COMMAND} -E copy_directory ${CMAKE_CURRENT_LIST_DIR} ${CMAKE_BINARY_DIR}/test/swagger-res
    DEPENDS ${MY_TARGET})
