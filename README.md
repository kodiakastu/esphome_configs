# Esphome Configs
## Repo for esphome_configs from my local Home Assistant.

There's some common "function" files:
  - Restart.yaml
    - Restart button for that device

There's also common configuration file for those boards:
  - d1-mini.yaml (ESP8266)
	- GPIO Header Pinout
	- DEVICENAME (esphome.name, sensor.wifi_signal.name)
	- status_led assigned to D4 based on the hardware onboard
  
  - esp-wrover-kit.yaml (ESP32)
	- Link to esp32 reference GPIO
	- DEVICENAME (esphome.name, sensor.wifi_signal.name)
	- board type, esp32_ble_tracker, bluetooth_proxy.active, wifi reference.
  
  - LilyGO-T-ETH-POE.yaml (ESP32)
    - GPIO Header Pinout
    - DEVICENAME (esphome.name, text_sensor.ethernet_info.ip_address.name), DEVICE_NAME (ethernet.id) for easy naming and variables in the main config file
    - board type, esp32_ble_tracker, bluetooh_proxy.active, Ethernet, SPI & I2C are defined, based on the hardware onboard and free pins
