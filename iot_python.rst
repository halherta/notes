**********************************************
Potential Resources For IOT and Python courses
**********************************************

Hardware
########
* `Raspberry pi $(35) <http://www.raspberrypi.org>`_

    - Linux SBC. Can run full blown CPython 3 and used as a portable computer
    - Can utilize virtually any python3/2 library
    - Has additional costs for power adapter SD card cables e.t.c
    - No Built-in ADC
    - Low cost Raspberry Pi Zero hardware $(11-15) but harder to source (limit 1 per customer)
    - Has GPIO/SPI/I2C/UART/1-2 channels PWM
    - Libraries of Note:
        - WiringPi (IO)
        - RPi.GPIO (IO)
        - GPIO Zero (IO)
        - Flask (Web Microframework)
        - Tornado (Web Microframework)

* `WiPy 3.0 $(30) <https://pycom.io/product/wipy-3/>`_

    - Runs 'Micropython <http://www.micropython.org>'_ a stripped down version of Python 3 running on bare metal
    - Uses an ESP32 part, dual core, WiFi, Bluetooth and plenty of IO.
    - 4MB SpiRAM
    - Comes with a plethora of libraries (Web frameworks, IO, MQTT e.t.c)
    - PWM/ADC/DAC/GPIO/SPI/I2C/UART more
    - Doesn't run Linux and is lower power than RPi 

* Other ESP32 ports ($11 - $50):
    - Run an alternative but more open version of micropython
    - Some come with 4MB SpiRAM but not all 
    - Cheaper than WiPy
    - Comes with a plethora of libraries (Web frameworks, IO, MQTT e.t.c)
    - PWM/ADC/DAC/GPIO/SPI/I2C/UART more
    - Uses an ESP32 part, dual core, WiFi, Bluetooth(not yet supported) and plenty of IO.
    - Libraries of Note:
        - PicoWeb 


Software
########
- `Thingsboard <http://www.thingsboard.io>`_
   Interesting opensource dashboard software that can talk MQTT
- `Paho MQTT client <https://www.eclipse.org/paho/>`_

 