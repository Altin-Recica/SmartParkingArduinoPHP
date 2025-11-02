# Smart Parking Project

This project is an implementation of a smart parking system using ESP32 and various sensors. It demonstrates real-time parking space monitoring, automated alerts, and I2C communication with LCD displays.

## Example Videos

* [Smart Parking Example 1](https://www.youtube.com/watch?v=-9s9QkpRzWs)
* [Smart Parking Example 2](https://www.youtube.com/watch?v=dZ57WLIyS04)

## System Diagram

![System Diagram](https://user-images.githubusercontent.com/84501094/158832059-2c38246a-ee87-4d1b-a5ea-6ecb2f757b86.png)

## Fishke Display

![Fishke](https://user-images.githubusercontent.com/84501094/160782711-9564a1ec-d0d3-4059-baf9-ccc0a74341c6.png)

## Construction Example

![Construction](https://user-images.githubusercontent.com/84501094/159648242-1bc935f7-010b-4e95-8e65-6d71c42076b8.png)

## I2C Address Scan Results

```
I2C device found at address hex: 0x7A dec: 122 (Parking 1)
I2C device found at address hex: 0x70 dec: 112 (Parking 2)
I2C device found at address hex: 0x7B dec: 123 (Parking 3)
I2C device found at address hex: 0x72 dec: 114 (Parking 4)
I2C device found at address hex: 0x78 dec: 120 (Parking 5)
I2C device found at address hex: 0x79 dec: 121 (Parking 6)
I2C device found at address hex: 0x27 dec: 39 (20x4 LCD)
```

## Bibliography / References

* Interface Chips, [Easy I2C: Introduction to I2C](https://www.youtube.com/watch?v=qeJN_80CiMU)
* Lastminuteengineers, [Interface an I2C LCD with Arduino](https://lastminuteengineers.com/i2c-lcd-arduino-tutorial/)
* Robtillaart, [MultiSpeed I2C Scanner](https://forum.arduino.cc/t/multispeed-i2c-scanner-50-100-200-400-khz/192325)
* Santos, Sara, [ESP32/ESP8266 Insert Data into MySQL Database](https://randomnerdtutorials.com/esp32-esp8266-mysql-database-php/)
* Campbell, Scott, [Basics of the I2C Communication Protocol](https://www.circuitbasics.com/basics-of-the-i2c-communication-protocol/)
* Sunfounder, [E18-D80NK Infrared Photoelectric Switch Sensor](http://wiki.sunfounder.cc/index.php?title=E18-D80NK_Infrared_Photoelectric_Switch_Sensor)
* w3schools, [PHP MySQL Select Data](https://www.w3schools.com/php/php_mysql_select.asp)

## Hardware Resources

* [Ultrasonic Sensor SRF02](https://www.robot-electronics.co.uk/htm/srf02techI2C.htm)
* [Datasheet SRF02](https://www.datasheet4u.com/datasheet-pdf/ETC/SRF02/pdf.php?id=625578)
* [ESP32 Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf)
* [RGB LED Pinout](https://www.electronicoscaldas.com/datasheet/LED5D-RGB-CA.pdf)
* [Servo SG90 Datasheet](http://www.ee.ic.ac.uk/pcheung/teaching/DE1_EE/stores/sg90_datasheet.pdf)
* [IR Sensor Info](http://wiki.sunfounder.cc/index.php?title=E18-D80NK_Infrared_Photoelectric_Switch_Sensor)

## Software Resources

* **PHP:** Server-side scripting language for dynamic content and database interaction.
* **SQL:** Standard language for relational database management.
* **WAMP:** Windows, Apache, MySQL, PHP stack for local development.
* **HTTP:** Protocol for data transmission over the web.
* **CSS:** Stylesheet language for designing web pages.
* **Arduino IDE:** Development environment for writing Arduino sketches.

## Notes

* ESP32 chosen over Arduino for better Wi-Fi support and processing power.
* ESP32 preferred over ESP8266 due to improved GPIO and peripheral support.
* Servomotors selected for precise control compared to DC or stepper motors.
* I2C communication used for LCD and sensor integration.
* PHP and MySQL handle backend data logging and retrieval.
