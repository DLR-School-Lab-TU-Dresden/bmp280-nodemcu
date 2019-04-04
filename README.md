# BMP280 + NodeMCU V2

Der Adafruit-Beispielcode läuft unverändert auf dem NodeMCU-Board. Wird nicht das Adafruit-, sondern das GY-BMP280-Breakout-Board verwendet, müssen für die Kommunikation via I2C die zwei Pins CSB und SD0 auf VCC gelegt werden.

## Anschluss des Sensors (I2C)

- SCL: D1 (GPIO 5)
- SDA: D2 (GPIO 4)
- CSB: VCC (für I2C)
- SD0: VCC (für Adresse 0x77 wie bei BMP180)

## Weiterführende Links

- [BMP280 and ESP8266](https://myesp8266.blogspot.com/2016/12/bmp280-and-esp8266.html)
- [Adafruit-Tutorial](https://learn.adafruit.com/adafruit-bmp280-barometric-pressure-plus-temperature-sensor-breakout/overview)