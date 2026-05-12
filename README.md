# LED-Chaser
LED-Chaser is an Circular-shaped PCB, with WS2812B LEDs. It has built-in microphone so it can be reactive to music.

## How it works?
- Brain: It uses ATtiny85, which sends PWM signals to the WS2812B, receives data from the potentiometer and microphone.
- Power: We power it by USB-C.
- LEDs: The first pin of the first WS2812B receives data from ATtiny85 and forwards to the second WS2812B. The second LED does the same, all the way to the 24rd LED, it's output is floating.

# BOM
Click [here](/BOM.csv)
