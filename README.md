# STM32 GPIO Driver Demo

This repository contains a simple demonstration of a GPIO driver for STM32 microcontrollers. The driver provides basic functionality to initialize GPIO pins, set their modes, and toggle their states.

## Description

The demonstration consists of three main files:

1. **gpio.h**: This header file defines macros, constants, and function prototypes for working with GPIO pins on an STM32 microcontroller. It abstracts low-level register manipulations and provides a convenient interface for GPIO operations.

2. **gpio.c**: This source file contains the implementation of the GPIO driver functions. It includes functions to enable clock for GPIO ports, initialize GPIO pins, read input data, and write output data.

3. **main.c**: This source file contains the main program that demonstrates the usage of the GPIO driver. It initializes GPIO pins connected to LEDs and toggles their states in a loop, creating a blinking effect.

## Techniques Demonstrated

- **Understanding Masking Techniques**: In the `GPIO_Init` function, masking techniques are used to prepare the configuration for a specific GPIO pin. Bitwise AND and OR operations are employed to set or clear bits in the configuration register.

- **Bitwise Operations**: Throughout the codebase, bitwise operations are utilized to manipulate individual bits in register values. This includes setting or clearing specific bits to configure GPIO pins or read input data.

- **Register Configuration**: The code demonstrates how to configure GPIO registers according to the desired functionality of the GPIO pins. This involves setting modes, output types, and speeds for GPIO pins.

## Additional Skills Demonstrated

- **Reading STM32 Reference Manual**: The code reflects the understanding of the STM32 reference manual for STM32F4 microcontrollers. Register addresses, bit definitions, and configuration procedures are derived from the manual, showcasing the ability to navigate technical documentation.

- **Embedded C Programming**: The code is written in Embedded C, demonstrating proficiency in programming for embedded systems.

- **Microcontroller Peripheral Configuration**: The code demonstrates configuring microcontroller peripherals (GPIO) to interact with external components (LEDs).

## Usage

To use this GPIO driver demonstration, follow these steps:

1. Clone the repository to your local machine.
2. Open the project in an IDE that supports embedded development.
3. Compile the code and upload it to an STM32 microcontroller board.
4. Observe the blinking LEDs connected to the GPIO pins configured in the code.

## Author

**Ayoub Bnina**  
Email: bnina.ayoub@etudiant-fst.utm.tn  
Phone: (+216)93.180.051
