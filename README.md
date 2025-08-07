# lora-smd-rak3172sip
SMD breakout board based on the RAK3172-SiP LoRa module, allow replacement of Argos SMD by LoRa SMD

![N|Solid](https://arribada.org/wp-content/uploads/2022/01/arribada_web_logo_g.svg)
# LoRa SMD module
## Description 

The LoRa SMD module is a small PCB (2x2cm) dedicated to act as a standalone or a coprocessor for any new design which required a LoRa communication. 
The module is based on RAK3172-SIP (STM32WLE) processor ([information](https://docs.rakwireless.com/product-categories/wisduo/rak3172-sip/quickstart/)).

This repository is an altium project with the production files allowed. 

## Configuration
The module only required a power supply and an antenna to be ready to be used. 

The module is compatible with all argos-smd design, and could be tested with argos-smd-wings is an example of breakout board ready to be used with Adafruit Feather board nRF52840 or RP2040. Find ressources at the following link : https://github.com/arribada/argos-smd-wings

The default firmware used by RAK3172 SIP module is RAKwireless Uniefied Interface V3 ([RUI3](https://docs.rakwireless.com/product-categories/software-apis-and-libraries/rui3/overview/))

Like the Argos-SMD, this module will respond to [AT-Command](https://docs.rakwireless.com/product-categories/software-apis-and-libraries/rui3/at-command-manual/)

The module can be also configured thanks to the [WisToolBox](https://docs.rakwireless.com/product-categories/software-tools/wistoolbox/overview/).


## State
V0.1 : (2025/08/07) First iteration schematics + layout.

## Todo
