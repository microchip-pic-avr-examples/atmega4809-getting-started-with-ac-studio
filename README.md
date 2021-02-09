[![MCHP](images/microchip.png)](https://www.microchip.com)

# Getting Started with Analog Comparator (AC) Examples (Microchip Studio)

  This repository contains examples of bare metal source code for Analog Comparator (AC) as described in [TB3211 - Getting Started with Analog Comparator (AC)](https://ww1.microchip.com/downloads/en/Appnotes/TB3211-Getting-Started-with-AC-DS90003211.pdf) document from Microchip. The repository contains an Atmel Studio Solution with multiple projects:

  * [<strong>Analog Signal Pulse Duration Measurement:</strong>](Analog_Signal_Pulse_Duration_Measurement) In this use case, the AC peripheral will be used to measure the input signal period and pulse duration (for more details, see [<strong>Analog Signal Pulse Duration Measurement</strong>](Analog_Signal_Pulse_Duration_Measurement)).
  * [<strong>Level Crossing Detector:</strong>](Level_Crossing_Detector) This example shows a basic initialization and set up for the AC peripheral. The application monitors an analog input signal, compares it to a fixed voltage and notifies the user via interrupt and an output pin every time the input signal crosses the fixed voltage level. (for more details, see [<strong>Level Crossing Detector</strong>](Level_Crossing_Detector)).
  * [<strong>Preventing False Spike Detection:</strong>](Preventing_False_Spike_Detection) This example demonstrates the hysteresis features of the AC module that helps in avoiding frequent toggling of the AC when the positive input oscillates close to the negative input level. This application is similar to the level crossing detector application.. Additionally, it has the Hysteresis mode enabled (for more details, see [<strong>Preventing False Spike Detection</strong>](Preventing_False_Spike_Detection)).



## Related Documentation
More details and code examples on the ATMEGA4809 can be found at the following links:
- [TB3211 - Getting Started with Analog Comparator (AC)](https://ww1.microchip.com/downloads/en/Appnotes/TB3211-Getting-Started-with-AC-DS90003211.pdf)
- [ATMEGA4809 Product Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [ATMEGA4809 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=atmega4809)
- [ATMEGA4809 Project Examples in START](https://start.atmel.com/#examples/ATMEGA4809XplainedPro)


## Software Used
- Microchip Studio 7.0.2542 or newer [(https://www.microchip.com/mplab/microchip-studio)](https://www.microchip.com/mplab/microchip-studio)
- ATmega_DFP 1.6.364 or newer Device Pack


## Hardware Used
- ATMEGA4809 Xplained Pro [(ATMEGA4809-XPRO)](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)
