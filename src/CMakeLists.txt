add_library(gpmf-parser STATIC
    ${CMAKE_CURRENT_LIST_DIR}/GPMF_mp4reader.c
    ${CMAKE_CURRENT_LIST_DIR}/GPMF_parser.c
    ${CMAKE_CURRENT_LIST_DIR}/GPMF_utils.c
)

target_include_directories(gpmf-parser
    PRIVATE
        ${GMPF_PARSER_PUBLIC_INCLUDE_DIR}/gpmf-parser
    PUBLIC
        ${GMPF_PARSER_PUBLIC_INCLUDE_DIR}
)
