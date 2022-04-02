idf_component_register(
                        SRCS    "esp_pdp8.c"                       
                        INCLUDE_DIRS ".")

set_source_files_properties(esp_pdp8.c
    PROPERTIES 
    COMPILE_FLAGS -Wno-unused-variable 
    COMPILE_FLAGS -Wno-unused-function

)