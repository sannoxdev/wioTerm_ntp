# wioTerm_ntp
An example of using NTP to set a RTC on a Wio Terminal.


This example based on the Arduino WifiUdpNtpClient code. NTP servers can be called via name or ip address, use only servers that can
repsond to IPv4 requests. This is related to the Wifi stack on the Wio Terminal. The code was tested using the Arduino 1.8.13 IDE version.

## Dependencies
- Adafruit RTClib


    an excellent rtc library that includes some useful DateTime functions. Can be found here: https://github.com/adafruit/RTClib

- millisDelay

    a library to provide non-blocking delays, primarily used inside the main loop. 
Details can be found here:  https://www.forward.com.au/pfod/ArduinoProgramming/TimingDelaysInArduino.html