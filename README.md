# Raspberry Pi Pico Wireless Weather Station
Raspberry Pi Pico W Wireless Weather station. This was written in Python and takes advantage of PiicoDev attachments. 

# Dependencies

## Hardware

Requirement: Raspberry Pi Pico **W** or **WH**. The code is not meant for regular Picos and a Pico H. Get one from a trusty source
Requirement: PiicoDev Pico Breakout board. To hook up the bme280 sensor, you need the PiicoDev equipment. Get one from Altronics: <a href="https://www.altronics.com.au/p/z6419-raspberry-pi-piicodev-expansion-board-for-pico/"> https://www.altronics.com.au/p/z6419-raspberry-pi-piicodev-expansion-board-for-pico/ </a> <br>
Requirement: PiicoDev Cables. Get them at Altronics: <a href="https://www.altronics.com.au/p/z6597-piicodev-cable-200mm/">https://www.altronics.com.au/p/z6597-piicodev-cable-200mm/</a><br>
Requirement: BME280 Sensor. Get it at Altronics: <a href="https://www.altronics.com.au/p/z6581-picodev-BME280-atmospheric-sensor-board/">https://www.altronics.com.au/p/z6581-picodev-BME280-atmospheric-sensor-board/</a><br>

Optional and code not provided: Wind speed and rain measurer<br>

## Software
You are required to have MicroPython installed onto your Pico W. <a href="https://micropython.org/resources/firmware/RPI_PICO_W-20231005-v1.21.0.uf2">Click here</a> to download a MicroPython uf2 for a Pico W. <br>

### Pip packages
• PiicoDev (pip install piicodev, or install it via thonny) <br>
• Http server <br>
• If you live in australia and want to get external features like forecasting, install `weather_au` via thonny or `pip install weather_au` <br>



# Installation

This assumes that you have soldered header onto a Pico W, and put it in the breakout board. <br>

1. Install the required modules (PiicoDev, http, weather_au [optional])
2. Copy over as `main.py`
3. Hook up your BME280 to one of the ports on the breakout board
4. Run and enjoy

## Rights and copyright

(C) Andrew's Abnormal for the code. All rights reserved. This code may be used in a production enviroment without any permission.<br>
PiicoDev is owned by Core Electronics Australia. <br>
Raspberry Pi and Raspberry Pi Pico are owned by Raspberry Pi Foundation in the UK. <br>
Altronics is owned by Altronics (r/technicallythetruth) <br>
I thank Tony Allan for the `weather-au` package: https://github.com/tonyallan/weather-au


Any Enquires: <a href="mailto:andrewisabnormal@gmail.com">Email Me!</a><br>
