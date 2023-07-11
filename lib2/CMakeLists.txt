add_library(lib2 SHARED
        src/lib2/obj_lib2.cpp)

target_link_libraries(lib2 PUBLIC
        lib1)