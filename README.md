# ESP32 Random Test

A sample sketch demonstrating the problem in Sandeep Mistry's excellent LoRa library's `random()` function. See [this issue](https://github.com/sandeepmistry/arduino-LoRa/issues/394) for context.

This was written for ESP32, but is easily adaptable to other platforms. The code runs on TTGO series. A T-Beam in this case, but it'll work as is with basically any LoRa-equipped TTGO or Heltec ESP32 device.

See:

![Generating Random Numbers with LoRandom](LoRandom.png)

vs

![Generating Random Numbers with LoRaClass::random](SandeepRandom.png)
