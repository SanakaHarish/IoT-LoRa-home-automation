# IoT-LoRa-home-automation-
Automated home appliances switching using LoRa technology

PROJECT DESCRIPTION: This project aims to switch appliances in home like lamp, fridge, geyser, fan etc., from anywhere else on this Earth like work place, market etc., using a smartphone application connected to internet.

Briefly Hardware components needed for the project:
1)Microcontroller board
2)LoRa module
3)Relay

WORKING PRINCIPLE: When User selects ON/OFF option in smartphone in order to switch appliance, this command will be sent to ‘Firebase cloud’ A cloud service from Google.Using Heltec WiFi-LoRa gateway, this signal will be communicated to receiver LoRa module which can communicate with microcontroller which is placed in some reachable radius from gateway which in turn Supplies 5V/does not supply 5V to relay module which will switch ON or switch OFF appliance like bulb.

