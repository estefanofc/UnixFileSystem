cmake_minimum_required(VERSION 3.16)
project(P5)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(P5
        alias.h
        bfs.c
        BFS.docx
        bfs.h
        BFSDISK
        bio.c
        bio.h
        deb.c
        deb.h
        errors.c
        errors.h
        fs.c
        fs.h
        main.c
        cmake-build-debug/CMakeFiles/P5.cbp
        P5.depend
        P5.layout
        p5test.c
        p5test.h
        README.md)
