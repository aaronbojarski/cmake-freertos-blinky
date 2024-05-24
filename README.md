# stm32h723-cmake-freertos-blinky
Blinky example for NUCLEO-H723ZG using freertos. Two threads run that both control one of the onboard LEDs.


# VS Code
To compile the code the official VS Code extension "STM32 VS Code Extension" was used. It can install all the dependencies automatically once the project is opened. It can then be used to compile and flash.
Additionally CubeMX, CubeCLT, STMCUFinder are needed. (Can be installed from ST webpage.)


# Project setup
Used CubeMX to generate the files. Mostly followed [this post](https://www.digikey.com/en/maker/projects/getting-started-with-stm32-introduction-to-freertos/ad275395687e4d85935351e16ec575b1) adapted to the H723. 
When generating the files make sure to use "CMake" as the option for Toolchain/IDE.