I2C контроллер для дисплеев LCD1602

Необходимые компоненты:
 - PCF8574P
 - 2 резистора 4.7к
 - резистор 6.2к
 - резистор 820 Ом
 - конденсатор 0,47 мкф

Подключение к платам:
    UNO  - A4(SDA), A5(SCL);
    Mega - 20(SDA), 21(SCL);
    Leonardo- 2(SDA), 3(SCL);
    Due - 20(SDA), 21(SCL),SDA1,SCL1;

Для работы устанавливаем библиотеку LiquidCrystal_I2C ( /libs/LiquidCrystal_I2C.zip )
Открываем любой пример из библиотеки.
