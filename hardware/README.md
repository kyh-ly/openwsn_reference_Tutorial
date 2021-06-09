# Hardware support openwsn

+ [Instruction](## Instruction)


## Instruction


First figure out the nouns:  

* 'mote' is a board with possibly various chips on it, like TelosB, CC2531EMK
* 'system-on-chip' is a single chip which contains both a micro-controller and a radio, like STM32WB55,nrf52840DK.
* 'micro-controllers' is a mcu which offers the compute service without radio transmit function, like stm32f10x,stm8x.
* 'IEEE802.15.4 radio' is a RF transceiver, like CC1101

## Motes

A 'mote' is a board with possibly various chips on it .  

|name |micro-controller|radio|
|:---:|:--------------:|:---:|
|TelosB|MSP430f1611|CC2420|
|GINA|MSP430f2618|AT86RF231|
|Zolertia Z1|MSP430F2617|CC2420|
|CC2531EMK|8051|CC2520(Soc)|
|NRF52840DK|PCA10056|nrf52840|
|Firefly|ATmega1281|CC2420|
|MICAz|ATmega1281|CC2420|


## sysntem-on-chip

A 'system-on-chip' is a single chip which contains both a micro-controller and a radio.   

|name|description|
|:----:|:-------:|
|STM32WB|Arm4 core running at 64 MHz (application processor) and Arm Cortex-M0+ core at 32 MHz (network processor)|
|Freescale MC13224V|ARM7, 32-bit, 128kBROM/96kBRAM|
|CC2530|8051CPU,32/64/128/256KB FLASH, 32MHz,8KB SRAM|
|CC2538|ARM Cortex-M3,32MHz,512/256/128KB Flash,32KB RAM|

