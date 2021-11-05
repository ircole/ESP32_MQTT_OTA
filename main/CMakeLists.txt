# Embed the server root certificate into the final binary
idf_build_get_property(project_dir PROJECT_DIR)
idf_component_register(SRCS "mqttOta.c"
							"mqttOta.h"
							"wifi.c"
							"wifi.h"
                    INCLUDE_DIRS "."
                    )
