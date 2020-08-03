project(mxli-cli)

add_executable(mxli "")
target_sources(mxli PRIVATE mxli.c)
target_link_libraries(mxli PRIVATE mxli-lib)
