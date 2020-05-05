# IoT-LoRa-home-automation
Automated home appliances switching using IoT coupled with LoRa technology

PROJECT DESCRIPTION: This project aims to switch appliances in home like lamp, fridge, geyser, fan etc., from anywhere else on this Earth like work place, market etc., using a smartphone application connected to internet.

Briefly Hardware components needed for the project:
1)Microcontroller board- arduino nano
2)LoRa module- Ai thinker's Ra-02  
3)Relay

WORKING PRINCIPLE: When User selects ON/OFF option in smartphone in order to switch appliance, this command will be sent to ‘Google Firebase cloud’ A cloud service from Google. Using 'Heltec WiFi-LoRa gateway' which can access this cloud using secret key being fed with code, this signal will be communicated to receiver LoRa module which will communicate with microcontroller.Which in turn Supplies 5V/does not supply 5V to relay module which will control AC voltage switching i.e., switch ON or switch OFF appliance like bulb.
