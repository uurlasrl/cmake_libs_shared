add_library(lib1 SHARED
        src/lib1/obj_lib1.cpp)

target_include_directories(lib1 PUBLIC
        src/lib1)