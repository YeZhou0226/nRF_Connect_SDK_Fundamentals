# nRF_Connect_SDK_Fundamentals
Tutorial from DevAcademy

https://academy.nordicsemi.com/courses/nrf-connect-sdk-fundamentals/

Lesson 1 – nRF Connect SDK Introduction
Understand the structure and content of the nRF Connect SDK
Learn how to download and install the nRF Connect SDK
Learn how to set up the nRF Connect for VS Code extension pack
Examine west, which is a core command-line utility in the nRF Connect SDK
Learn how to build applications
Learn how to flash applications to boards
Run your first application blinky, which toggles an LED on your Nordic-based board

Lesson 2 – Reading buttons and controlling LEDs
Examine the devicetree API <zephyr/devicetree.h>
Examine board-level devicetree .dts
Examine SoC-level devicetree .dtsi
Understand the purpose of devicetree binding files (.yaml) and the compatible property
Understand the device driver model <zephyr/device.h>
Analyze the decoupling between a device driver API and a device driver implementation and the need to have a device pointer
Examine the generic GPIO interface APIs <zephyr/drivers/gpio.h>
Practice through hands-on exercises configuring GPIO pins and learn how to read/write to/from GPIO pins and how to set up interrupts for input GPIO pins

Lesson 3 – Elements of an nRF Connect SDK application
Understand the use of Kconfig configuration files to enable and configure the different software modules available in the nRF Connect SDK
Examine an application configuration file and a board configuration file and understand the relation between them
Learn how to explore the available configuration options of a certain software module using guiconfig
Understand multi-image builds, and how a child-image is added to your application
Practice through hands-on exercises how to create an application from scratch, and how to add modules using Kconfig and modify the devicetree

2023.2.13: Finished lesson 3. For Macbook, using built-in terminal in VS Code called "NRF TERMINAL" instead of PuTTY for serial output.
