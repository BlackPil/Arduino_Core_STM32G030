## Getting Started

This repo is available as a package usable with [Arduino Boards Manager](https://www.arduino.cc/en/guide/cores).

Add this link in the "*Additional Boards Managers URLs*" field:

https://raw.githubusercontent.com/BlackPil/Arduino_Core_STM32G030/main/package_blackpillstm32g030_index.json


## Hello World Example

/*
 * Black Pill STM32G030
 * Hello World(Blinker)
 * 
 * Author: Soheil Moradi
 * Sohil2000net@gmail.com
 */

void setup() {
pinMode(LED_BUILTIN,OUTPUT);
}

void loop() {
digitalWrite(LED_BUILTIN,!digitalRead(LED_BUILTIN));
delay(250);
}
