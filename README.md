# Mini-task-2-CFI-IITM

# Project 1 : IOT Home Security System with Particle Argon

**Problem Statement** - Get notifications when your house door is opened, Home Security at the touch of your fingers! 

**Ideation** -

**Understand the device mechanism** -




# Project 2 : Ambient Sound Light Show

**Problem Statement** - Using frequency content we will analyze ambient sound and display it on strip of LEDs

**Ideation** -

**Understand the device mechanism** -

Electret microphone -> 2k2 bias resistor

SPI buss connections -> DotStar LED strip and an analog pot input

Arduino IDE + Sony Spresense board -> serial port with a terminal to get a reading on the processing time
 
|Parts Used                   | Replacable with | Advantages | Disadvantage|
|-----------------------------|-----------------|------------|-------------|
|Sony Spresense boards |(main & extension)|Very efficient| Costly|
|Adafruit dotstart LED strip  |Citra LED strip  |It's cheap  |    --       |
|Electret microphone          |       --        |Auto gain control|   --   |
|Rotary potentiometer         |       --        |High efficiency | --   |

Things on which we could work to make device more efficient:
* Instead of Adafruit dotstar LED strip which costs 3800 inr we could use Citra LED strip which costs 300 inr and works same.
* Before connecting to amplifier we will use isolation transformer so that it will clear out any noise present...
