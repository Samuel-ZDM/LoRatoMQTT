# LoRatoMQTT
This is quick and dirty bridge from LoRa to MQTT. Arduino sketch for Heltec ESP32 LoRa. Bridge listening for LoRa packet, take first byte of it
and translate to MQTT topic iho-iot/<srcaddr>  and transmit rest of the packet as MQTT message.

