# Digital Temperature Sensor Project

## Overview
Welcome to the Digital Temperature Sensor project by Nikhil Saroya. This project utilizes the ATmega328p microcontroller to create a temperature control system. The system measures both internal and external temperatures, allowing users to set and control the temperature using an LCD display and buttons. The project includes features such as a furnace control mechanism and a user-friendly interface.

## Features
- **Temperature Sensors:** The project incorporates both internal and external temperature sensors to provide accurate temperature readings.
- **User Interface:** Users can interact with the system using three buttons to set and adjust the desired temperature.
- **Furnace Control:** The system automatically controls the furnace based on the selected mode (internal or external) and user-set temperature.
- **LCD Display:** The project utilizes an LCD display to present temperature readings and system status in a clear and organized manner.

## Hardware Requirements
- ATmega328p microcontroller
- Temperature sensors (internal and external)
- LCD display
- Three buttons for user input
- LED indicator for furnace status

## How to Use
1. Connect the ATmega328p microcontroller to the required sensors and components.
2. Upload the provided code to the microcontroller.
3. Power on the system.
4. Use the buttons to set the desired temperature and choose between internal and external modes.
5. Observe the LCD display for real-time temperature readings and furnace status.

## Code Overview
The code includes functions for reading internal and external temperatures, furnace control logic, user input handling, and LCD display formatting. It uses the AVR C programming language and standard AVR libraries.

```c
// Example Code Snippet
float sensor_internal(); // Function for reading internal temperature
float sensor_external(); // Function for reading external temperature
void furnace1(); // Function for furnace control
void input(); // Function for handling user input
void print(); // Function for formatting and displaying information on the LCD
