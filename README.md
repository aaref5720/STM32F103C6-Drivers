# STM32F103C6 Drivers

This repository contains essential drivers for STM32F103C6 microcontroller, organized into two main folders: MCAL and HAL.

## MCAL (Microcontroller Abstraction Layer)

The MCAL folder encompasses low-level drivers that directly interface with the hardware peripherals of the STM32F103C6 microcontroller. These drivers provide an abstraction layer to interact with the microcontroller's hardware components efficiently.

### Included Drivers:
- **USART:** Driver for USART (Universal Synchronous/Asynchronous Receiver/Transmitter) communication.
- **SPI:** Driver for SPI (Serial Peripheral Interface) communication.
- **RCC:** Driver for RCC (Reset and Clock Control) module.
- **I2C:** Driver for I2C (Inter-Integrated Circuit) communication.
- **GPIO:** Driver for General Purpose Input/Output pins.
- **EXIT:** Driver for External Interrupts.

## HAL (Hardware Abstraction Layer)

The HAL folder contains higher-level drivers that build upon the MCAL layer, providing simplified APIs for interacting with complex peripherals and external devices.

### Included Drivers:
- **EEPROM_driver:** Driver for EEPROM (Electrically Erasable Programmable Read-Only Memory) interfacing.
- **LCD_driver:** Driver for Liquid Crystal Display (LCD) interfacing.
- **Keypad_driver:** Driver for interfacing with a keypad.

## Usage

To utilize these drivers in your STM32F103C6 projects, simply include the necessary files from the respective folders in your project. Refer to the documentation within each driver for detailed usage instructions.

## Contributing

Contributions to enhance or expand the functionality of these drivers are welcome! Feel free to submit pull requests or open issues for any bugs or feature requests.


