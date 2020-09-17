W5500_STM32F4_SPI_DMA
=====================

This repository is for releasing source codes about the enhancement of W5500 throughput using ST's SPI DMA method.
These codes were designed and tested on ST's Nucleo-F401RE board using STM32F401RE.
The related post is on http://javakys.wordpress.com/2014/09/04/upgrade-w5500-throughput-on-nucleo-stm32f401re-using-spi-dma/

Directory "Application" and "Ethernet" have the driver codes for WIZnet W5500 and W5200 and loopback test application codes.
Directory "PlatformHander" consists of all initialization block for MCU dependent peripherals.
Codes for SPI DMA methods are here.

##STM32F4xx and WIZ550io Connection

| Nucelo  PIN   | WIZ550io |NAME	|
|---------------|----------|--------|
|PA_5    	    | J1_5     |SCLK   	|
|PA_6 	        | J1_4     |MOSI	|
|PA_7 	        | J1_3     |MISO	|
|PB_6 	        | J1_6     |CSn		|
|PA_11	        | J2_3     |RSTn    |
|PA_1	        | J2_2     |RDY     |
|3.3V           | J1_8     |3.3V    |
|GND            | J1_1     |GND     |

## W5500 Test Loopback
![W5500_SPIDMA_24MHz](https://user-images.githubusercontent.com/9648281/93420590-3ac13e00-f8ea-11ea-9a36-fba6b9065ce4.png)
## W5500 Recv Only using Iperf 
To be add
## W5500 Send Only using Iperf
To be add


##OScilloscope
![scope_1](https://user-images.githubusercontent.com/9648281/93421375-28e09a80-f8ec-11ea-84fa-b809b2d179b5.png)




