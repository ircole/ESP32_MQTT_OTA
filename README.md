# ESP32 OTA with MQTT transport for Thingsboard

This example was derived from the native_ota_example and mqtt_firmware_client.py.  It is meant to be a 
starting point as requirements vary by projects. The code isn't pretty but is functional.  

Reference URL:  https://thingsboard.io/docs/user-guide/ota-updates/

There are several other Thingsboard hits for OTA which may prove helpful.

## Configuration

Set the ssid, password, MQTT broker URL, port, and the Thingsboard device token using menuconfig. The version
number needs to be changed in mqttOta.h for each build as this is the version number used for determining if the
firmware needs to be updated.  
