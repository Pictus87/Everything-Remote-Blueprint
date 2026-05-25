# This is a blueprint for the "Everything-Remote" by [@Stock-Pot](https://github.com/TheStockPot)

## Functions:  
- The Blueprint offers collapsable section for each button and all button have single, double and long-press actions.
- Optional names in the section keep easier overview of the functions you did inside.
- Also you  see the GPIO Names in additon to cross check with the following picture of the buttons.

## Improved ESP-Home Firmware:  
- added "device name" as substitution to easier identify different remotes by the blueprint
- There is also now a battery voltage measurement function inside including percentage calculation
    - To make this fully work you need to solder 2x 100k Ohm resistors between 3.3V and VP and GND and VP on the lolin board
    - If you did, then you just need to uncomment the section in the ESPHome FW

## Setup:  
- Flash the ESPHome code to your remote via ESPHome in your HA or the webapp (https://web.esphome.io/)
- Import the Automation to your HA --> 
- create the automation and have fun.

<!-- markdownlint-disable MD013 -->
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FPictus87%2FEverything-Remote-Blueprint%2Frefs%2Fheads%2Fmain%2Feverything_remote_blueprint.yaml)
<!-- markdownlint-enable MD013 -->

## Button Layout (by [@Stock-Pot](https://github.com/TheStockPot))

<img width="750" height="1150" alt="image" src="https://github.com/user-attachments/assets/43992092-0712-4816-b0cc-456937f6be3d" />
