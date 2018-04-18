cmake_minimum_required(VERSION 3.9)
project(libb2)

set(CMAKE_CXX_STANDARD 11)

add_executable(libb2
        src/blake2-config.h
        src/blake2-dispatch.c
        src/blake2-impl.h
        src/blake2-kat.h
        src/blake2.h
        src/blake2b-load-sse2.h
        src/blake2b-load-sse41.h
        src/blake2b-ref.c
        src/blake2b-round.h
        src/blake2b-test.c
        src/blake2b.c
        src/blake2bp-test.c
        src/blake2bp.c
        src/blake2s-load-sse2.h
        src/blake2s-load-sse41.h
        src/blake2s-load-xop.h
        src/blake2s-ref.c
        src/blake2s-round.h
        src/blake2s-test.c
        src/blake2s.c
        src/blake2sp-test.c
        src/blake2sp.c)
