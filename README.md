# Learn How to make a Ambient-light for your monitor

*You can refer to this video by AlexGyver to set up Ambibox, just follow this hardware and code as this is the improved version.*
VIDEO LINK: https://youtu.be/tx5GxvFgkh0?si=PZhO9Q06oYIUAtC-

**Things Needed:**
<pre>
  1x Arduino UNO (hardware)
  1x Neopixel strip - WS2812B (hardware)
  3x Potentiometer (hardware)
  1x USB cable (hardware)
  1x RGB LED (hardware)
  1x Switch  (hardware)

  Arduino IDE (software)
  Ambibox (software)
</pre>
______________________________________________________________________________________________________________________________

**Hardware Connections:**
<pre>
  NEOPIXEL:
    VCC - Arduino 5V if the strip needs 1A, but if it needs more than 1A, then connect to external PSU.
    GND - Arduino GND if VCC is connected to arduino 5V, but to external PSU GND if VCC is connected to external PSU
    Signal - D13
  ---------------------------------------------------------------------------------------------------------------------------
  SWITCH:
    Terminal 1: Arduino 5V
    Wiper: D12
    Terminal 2: Arduino GND
  ---------------------------------------------------------------------------------------------------------------------------
  RGB LED:
    Red: D3
    Green: D5
    Blue: D6
    Common Anode / Common Cathode: 3.3V or GND
  ---------------------------------------------------------------------------------------------------------------------------
</pre>
