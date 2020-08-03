project(ramreader)

add_executable(ramreader "")
target_sources(ramreader PRIVATE ramreader.c)
target_link_libraries(ramreader PRIVATE mxli-lib)
