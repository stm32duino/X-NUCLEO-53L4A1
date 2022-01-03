# X-NUCLEO-53L4A1

Arduino library to support the X-NUCLEO-53L4A1 based on VL53L4CD ranging sensor.
This sensor uses I2C to communicate. An I2C instance is required to access to the sensor.
The APIs provide simple distance measure in both polling and interrupt modes.

## Examples

There are 2 examples with the X-NUCLEO-53L4A1 library.

* X_NUCLEO_53L4A1_HelloWorld: This example code is to show how to get proximity
  values of the onboard VL53L4CD sensor in polling mode.

* X_NUCLEO_53L4A1_HelloWorld_Interrupt: This example code is to show how to get proximity
  values of the onboard VL53L4CD sensor in interrupt mode.

## Dependencies

This package requires the following Arduino libraries:

* STM32duino VL53L4CD: https://github.com/stm32duino/VL53L4CD


## Documentation

You can find the source files at  
https://github.com/stm32duino/X-NUCLEO-53L4A1

The VL53L4CD datasheet is available at  
https://www.st.com/content/st_com/en/products/imaging-and-photonics-solutions/proximity-sensors/vl53l4cd.html