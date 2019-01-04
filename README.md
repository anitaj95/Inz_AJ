ble_app_uart_saadc
==================
 
Folder in the nRF5_SDK_15.2.0_9412b96\examples\ble_peripheral\ble_app_uart_saadc contains project "Wireless measurement system for telemedical application". This application allows to send the data from EKG sensor using Bluetooth Low Energy.
 
 Requirements
 -------------------------------------
 Required devices:
 - Bluetooth Low Energy nRF52832
 - Development Kit nRF52
 - EKG sensor AD8232
 
 Required tools for creating and compiling the code:
 - nRF5 SDK 15.2.0
 - GNU toolchain for ARM Cortex-M
 - GNU make
 - Eclipse
 
 Required tools for programming the microcontroller:
 - SEGGER Embedded Studio
 - nRFgo Studio
 
 How to use the project
 -------------------------------------
 - install and configure programs mentioned above,
 - compile code with command 'make' - in the terminal (creating a file .hex),
 - upload generated file and Softdevice S132 to Development Kit nRF52 by nRFgo Studio.
