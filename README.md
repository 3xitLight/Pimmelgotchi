# Pimmelgotchi
Tamagotchi clone for Arduino | Pimmelgotchi  based on https://github.com/alojzjakob/Tamaguino

#### Hardware:
- Arduino Uno or Arduino Pro Mini
- SSD1306 128x64 OLED display (I2C version)
- Piezo buzzer
- Push Buttons
- Breadboard

#### Libraries:
- Adafruit GFX
- Adafruit SSD1306

#### Code:


###### Edit as needed
```
...

#include <SPI.h>
#include <Wire.h>
#include <Adafruit_GFX.h>
#include <Adafruit_SSD1306.h>

#define OLED_RESET 4
Adafruit_SSD1306 display(OLED_RESET);

const int button1Pin = 9;
const int button2Pin = 8; 
const int button3Pin = 7; 

const int sound = 6; 

int button1State = 0;
int button2State = 0;
int button3State = 0;

...
```