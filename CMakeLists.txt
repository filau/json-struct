cmake_minimum_required(VERSION 3.16)
project(json-struct)


add_library(json-struct STATIC
        src/json/json_mapper.c
        src/json/json.c
)

target_include_directories(json-struct PUBLIC
        include
        include/json
)
