# Raspberry to Arduino Shield Expansion board


[Raspberry Pi To Arduino Shield Expansion Board Adapter Board Add-on](http://www.icstation.com/raspberry-arduino-shield-expansion-board-adapter-board-p-5710.html)

![pic](http://www.icstation.com/images/big/products/5710_4_8525.jpg)

[Documentación del creador del producto](https://www.itead.cc/wiki/RPI_Arduino_Sheild_Add-on_V2.0S)

## Pros

* Facilita el montaje de shields
* Permite conecta muchos servos o sensores de 3 cables directamente
* Facilita conectar dispositivos I2C o serie de forma sencilla
* Permite cambiar la alimentación entre 5V y 3.3V
* Continúa el bus de la Raspberry para poder añadir más dispositivos

## Mejoras

* Añadiría un chip ADC conectado por I2C
* Permitir usar una alimentación externa de los grupos de 3 pines


## Ejemplos

### Controlando un relé

### Leyendo un sensor de temperatura/humedad DHT11

![pinout DHT11](http://domoticx.com/wp-content/uploads/DHT11-Pinout-keyes.jpg)

[Tutorial Adafruit](https://learn.adafruit.com/dht-humidity-sensing-on-raspberry-pi-with-gdocs-logging?view=all)

### Controlando un servo

[Tutorial Adafruit ](https://learn.adafruit.com/adafruits-raspberry-pi-lesson-8-using-a-servo-motor?view=all)

### Usando un LCD con interface I2C


* Activamos el i2c

INSTALL I2C-TOOLS AND SMBUS
Now we need to install a program called I2C-tools, which will tell us the I2C address of the LCD when it’s connected to the Pi. So at the command prompt, enter


      sudo apt-get install i2c-tools.

Next we need to install SMBUS, which gives the Python library we’re going to use access to the I2C bus on the Pi. At the command prompt, enter


      sudo apt-get install python-smbus.


Para detectar la dirección de la pantalla


      i2cdetect -y 1

[Tutorial de montaje](http://www.circuitbasics.com/raspberry-pi-i2c-lcd-set-up-and-programming/)

![pinout](https://github.com/javacasm/DomoticaOnlineDE/raw/master/Raspberry/images/RP2_Pinout.png)

[Tutorial adafruit de shield LCD](https://learn.adafruit.com/adafruit-16x2-character-lcd-plus-keypad-for-raspberry-pi?view=all)
