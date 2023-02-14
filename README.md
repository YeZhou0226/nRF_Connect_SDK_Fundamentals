# nRF_Connect_SDK_Fundamentals
Tutorial from DevAcademy

https://academy.nordicsemi.com/courses/nrf-connect-sdk-fundamentals/

Lesson 1 – nRF Connect SDK Introduction

1. Understand the structure and content of the nRF Connect SDK
2. Learn how to download and install the nRF Connect SDK
3. Learn how to set up the nRF Connect for VS Code extension pack
4. Examine west, which is a core command-line utility in the nRF Connect SDK
5. Learn how to build applications
6. Learn how to flash applications to boards
7. Run your first application blinky, which toggles an LED on your Nordic-based board

Lesson 2 – Reading buttons and controlling LEDs

1. Examine the devicetree API <zephyr/devicetree.h>
2. Examine board-level devicetree .dts
3. Examine SoC-level devicetree .dtsi
4. Understand the purpose of devicetree binding files (.yaml) and the compatible property
5. Understand the device driver model <zephyr/device.h>
6. Analyze the decoupling between a device driver API and a device driver implementation and the need to have a device pointer
7. Examine the generic GPIO interface APIs <zephyr/drivers/gpio.h>
8. Practice through hands-on exercises configuring GPIO pins and learn how to read/write to/from GPIO pins and how to set up interrupts for input GPIO pins

Lesson 3 – Elements of an nRF Connect SDK application

1. Understand the use of Kconfig configuration files to enable and configure the different software modules available in the nRF Connect SDK
2. Examine an application configuration file and a board configuration file and understand the relation between them
3. Learn how to explore the available configuration options of a certain software module using guiconfig
4. Understand multi-image builds, and how a child-image is added to your application
5. Practice through hands-on exercises how to create an application from scratch, and how to add modules using Kconfig and modify the devicetree

Lesson 4 – Printing messages to console and logging

Learn how to print strings and formatted strings to a console using printk()
1. Recognize the limitations of printk()
2. Learn how to print strings and formatted strings to a console using the logger module
3. Learn how to hex dump variables using the logger module
4. Explore the logger module features
5. Practice through hands-on exercises enabling/configuring software modules

2023.2.13: Finished lesson 3. For Macbook, using built-in terminal in VS Code called "NRF TERMINAL" instead of PuTTY for serial output. Use VCOM1 for NRF TERMINAL.

2023.2.14: Finished lesson 4. In Exercise2 proj.conf, make sure enable the logger module using "CONFIG_LOG=y".
