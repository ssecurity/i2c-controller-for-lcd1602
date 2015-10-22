I2C controller to display LCD1602

Required components:
  - PCF8574P
  - 2 4.7k resistor
  - 6.2k resistor
  - 820 ohm resistor
  - 0.47 uF capacitor


Connect to boards:
    UNO  - A4(SDA), A5(SCL);
    Mega - 20(SDA), 21(SCL);
    Leonardo- 2(SDA), 3(SCL);
    Due - 20(SDA), 21(SCL),SDA1,SCL1;

To use the library set LiquidCrystal_I2C (/libs/LiquidCrystal_I2C.zip)
Open any sample from the library.