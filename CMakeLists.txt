add_library(halfedge 
    src/trimesh.cpp
    include/halfedge/trimesh_types.h
    include/halfedge/trimesh.h
)

target_include_directories(halfedge PUBLIC include/)
