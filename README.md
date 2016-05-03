# Photocell
**WORK IN PROGRESS!**

## Overview

Photocells are sensors that allow us to measure light. This repository will provide useful (to me anyhow) utility C and Python source code for using photocells with IoT micro controllers such as Arduino and Micropython.

## Goals

* Convert: Resistance -> Volts -> ADC n-bit integer -> Lux/K
* Accumulate: Combine Lux measurments so that a meaningful amount of light for a given time period can be determined
  * How much light did a plant get?
  * How much UV exposure?
  * etc.

## CdS Photocells



### References

* [Adafruit Tutorial](https://learn.adafruit.com/photocells/overview)
* [Datasheet](https://cdn-learn.adafruit.com/assets/assets/000/010/127/original/PDV-P8001.pdf)
* [Datasheet](https://cdn-learn.adafruit.com/assets/assets/000/010/128/original/DTS_A9950_A7060_B9060.pdf)
