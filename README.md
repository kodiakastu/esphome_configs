# Esphome Configs
Repo for esphome_configs from my local Home Assistant.

There are some common files:
  - Restart.yaml
    - Restart button for that device
    
  - LilyGO-T-ETH-POE.yaml
    - GPIO Header Pinout
    - DEVICENAME (esp32-eth-device), DEVICE_NAME (esp32_eth_device) for easy naming and variables in the main config file
    - board type, bluetooh_proxy, Ethernet, SPI, I2C & ip_address are defined, based on the hardware onboard and free pins
