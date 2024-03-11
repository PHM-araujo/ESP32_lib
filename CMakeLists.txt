idf_component_register(SRCS "OTA/OTA.cpp" "Wetzel_Wifi/Wifi.cpp" "Wetzel_Memory/Memory.cpp"
                    INCLUDE_DIRS "OTA/" "Wetzel_Wifi/" "Wetzel_Memory/"
                    REQUIRES app_update esp_http_server esp_wifi nvs_flash)