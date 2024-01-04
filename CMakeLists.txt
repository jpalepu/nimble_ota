idf_component_register(SRCS "gap.c" "gatt_svr.c" "main.c" 
                    INCLUDE_DIRS "."
                   )

                   # REQUIRES  spi_flash bt freertos nvs_flash