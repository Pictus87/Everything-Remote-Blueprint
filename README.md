#This is the blueprint for the "Everything-Remote" made by [@Stock-Pot](https://github.com/TheStockPot)

##Functions:  
- The Blueprint offers collapsable section for each button and all button have single, double and long-press actions.
- Optional names in the section keep easier overview of the functions you did inside.
- Also you  see the GPIO Names in additon to cross check with the following picture of the buttons.

##Improved ESP-Home Firmware:  
- added "device name" as substitution to easier identify different remotes by the blueprint
- There is also now a battery voltage measurement function inside including percentage calculation
    - To make this fully work you need to solder 2x 100k Ohm resistors between 3.3V and VP and GND and VP on the lolin board
    - If you did, then you just need to uncomment the section in the ESPHome FW

##Setup:  
Flash the ESPHome code to your remote, create the automation for it and have fun.

##Button Layout (by [@Stock-Pot](https://github.com/TheStockPot))

<img width="750" height="1150" alt="image" src="https://github.com/user-attachments/assets/43992092-0712-4816-b0cc-456937f6be3d" />
