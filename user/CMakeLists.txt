project(basilisk-sandbox-user
    LANGUAGES C CXX
)

find_package(basilisk CONFIG REQUIRED)
include(CTest)

basilisk_add_ctest(karman SOURCE karman.c) 
