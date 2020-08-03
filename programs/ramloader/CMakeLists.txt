project(ramloader)

add_executable(ramloader "")
target_sources(ramloader PRIVATE ramloader.c)
target_link_libraries(ramloader PRIVATE mxli-lib)
