# Firmware
The firmware is developed for location tracking hardware based on the ESP32
Basic Firmware functions
  - scans for WiFi MAC addresses and uses RSSI to compute signal stength 
  - sends a packet via Sigfox/Lora comprised off: MAC addresses, RSSI and battery voltage
  - goes into deep sleep states and wakes up every N seconds to send a packet
  - can send a location packet 6 times per hour and have a battery life of 30+ days on a 300mAh battery
 
  
