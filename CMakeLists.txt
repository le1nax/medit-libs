add_library(meditpcan STATIC IMPORTED)
set_target_properties(meditpcan PROPERTIES
    IMPORTED_LOCATION "${CMAKE_CURRENT_LIST_DIR}/lib/PCANBasic.lib"
)

target_include_directories(meditpcan  INTERFACE "{CMAKE_CURRENT_LIST_DIR}/include")

