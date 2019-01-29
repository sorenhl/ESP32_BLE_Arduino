#Created by VisualGDB. Right-click on the component in Solution Explorer to edit properties using convenient GUI.

set(MY_BLE_SRCS
src/BLE2902.cpp src/BLE2904.cpp src/BLEAddress.cpp src/BLEAdvertisedDevice.cpp src/BLEAdvertising.cpp src/BLEBeacon.cpp src/BLECharacteristic.cpp src/BLECharacteristicMap.cpp src/BLEClient.cpp src/BLEDescriptor.cpp src/BLEDescriptorMap.cpp src/BLEDevice.cpp src/BLEExceptions.cpp src/BLEHIDDevice.cpp src/BLERemoteCharacteristic.cpp src/BLERemoteDescriptor.cpp src/BLERemoteService.cpp src/BLEScan.cpp src/BLESecurity.cpp src/BLEServer.cpp src/BLEService.cpp src/BLEServiceMap.cpp src/BLEUtils.cpp src/BLEUUID.cpp src/BLEValue.cpp src/FreeRTOS.cpp src/GeneralUtils.cpp
)
set(COMPONENT_SRCS ${MY_BLE_SRCS})
set(COMPONENT_ADD_INCLUDEDIRS "./src")
set(COMPONENT_PRIV_INCLUDEDIRS ../arduino-esp32/tools/sdk/include/bt ../arduino-esp32/tools/sdk/include/config ../arduino-esp32/cores/esp32 ../arduino-esp32/tools/sdk/include/nvs_flash ../arduino-esp32/tools/sdk/include/spi_flash)

register_component()
