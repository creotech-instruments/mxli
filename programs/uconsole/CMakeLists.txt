project(uconsole)

find_package(Threads REQUIRED)
find_package(PkgConfig REQUIRED)
pkg_check_modules(readline REQUIRED IMPORTED_TARGET readline)

add_executable(uconsole "")
target_sources(uconsole PRIVATE uconsole.c)
target_link_libraries(uconsole PRIVATE mxli-lib Threads::Threads PkgConfig::readline)
