idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS ".")

target_compile_definitions(${COMPONENT_LIB} PUBLIC "-DLV_HOR_RES_MAX=320")
target_compile_definitions(${COMPONENT_LIB} PUBLIC "-DLV_VER_RES_MAX=240")
target_compile_definitions(${COMPONENT_LIB} PUBLIC "-DLV_LVGL_H_INCLUDE_SIMPLE")
