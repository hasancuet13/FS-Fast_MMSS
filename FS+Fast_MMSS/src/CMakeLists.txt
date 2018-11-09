# cmake_minimum_required(VERSION <specify CMake version here>)
project(src)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(src
        ClosestSub.h
        CompatiblePairs.h
        CompressedLmers.h
        IndexScheduler.h
        main.cpp
        MotifWorker.h
        MyString.cpp
        MyString.h
        PairDist.h
        StringSet.h
        utils.cpp
        utils.h)
