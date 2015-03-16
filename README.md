Multicomm shield
================

![](http://www.sistemasorp.es/multicomm/multicomm.jpg)

Objetivo
________

Esta shield para Arduino se concibió en SpainLabs y está pensada para poder utilizar los módulos de comunicaciones más comunes de una forma sencilla.

![](http://www.sistemasorp.es/multicomm/modulos.png)

Características
_______________

Los módulos serie que pueden acoplarse son el ESP8266 (ESP-01), HC05 y HC06, XBEE y además existen unos pines independientes para utilizar un dispositivo USB2UART por software.

Los módulos SPI que pueden acoplarse son el NRF24L01 y NRF905.

Al tener Arduino un sólo puerto serie, únicamente se puede utilizar un módulo de comunicaciones serie a la vez, en cambio los que usan el puerto spi pueden ser utilizados al mismo tiempo.

Además la shield incorpora dos formas de conexión para ampliar la lista de módulos:
-Una aprovechando el zócalo para xbee, que puede ser activada o desactivada por un switch de 8 posiciones.
-Otra mediante un zócalo diseñado para placas de topos.

Lista de materiales
___________________

- **1 resistencia SMD 1206 de 10K** 0,01€ 
 http://es.aliexpress.com/item/-/1936731050.html
- **1 condensador SMD 1206 de 100nF** 0,01€
 http://es.aliexpress.com/item/Free-Shipping-100PCS-1206-104-100NF-0-1UF-1206-SMD-capacitance/1096160798.html
- **1 condensador SMD 1206 de 10UF** 0,02€
 http://es.aliexpress.com/item/QIAOTIAN-SMD-1206-Chip-Capacitor-10UF-106M-Y5V-10V-100PCS-Lot/1820137718.html
- **1 diodo SMT schottky** 0,02€
 http://es.aliexpress.com/item/Free-Shipping-100PCS-Schottky-Diode-1A-40V-1N5819-SS14-SMD-SMT/627622453.html
- **1 regulador SOT-223 ASM1117** 0,03€
 http://es.aliexpress.com/item/Free-Shipping-100PCS-Original-AMS1117-3-3-AMS1117-3-3V-AMS1117-1117-3-3V-1A-Voltage/1149210196.html
- **2 tiras de pines hembra de 2x4** 0,14€
 http://es.aliexpress.com/item/10x-2-54mm-2x4-Pins-Double-Row-Female-Straight-Header-Pitch-Socket-Pin-Strip-New/32243233137.html
- **1 tira de pines hembra de 2x7** 0,18€
 http://es.aliexpress.com/item/10PCS-2X7-Pin-14P-2-54mm-Double-Row-Female-Straight-Header-Pitch-Socket-Strip/1902481672.html
- **1 tira de pines hembra de 1x4** 0,07€
 http://es.aliexpress.com/item/40pcs-Golden-Single-Row-1x4-pins-2-54mm-Female-Header/877315473.html
- **2 tiras de pines hembra de 1x6** 0,08€
 http://es.aliexpress.com/item/-/2015371109.html
- **2 tiras de pines hembra de 1x10 2mm paso** 0,57€
 http://es.aliexpress.com/item/10-Pcs-Per-Lot-2mm-Pitch-10-Pin-Female-Single-Row-Straight-Pin-Header-Strip/32256838365.html
- **1 tira de pines macho de 1x40** 0,08€
 http://es.aliexpress.com/item/Free-Shipping-10pcs-40-Pin-1x40-Single-Row-Male-2-54-Breakable-Pin-Header-Connector-Strip/2035586129.html
- **1 switch dip de 8 posiciones** 0,19€
 http://www.ebay.co.uk/itm/50-pcs-DMR08T-Dip-Switch-SMD-8-Position-with-Tape-Seal-/261754060756

Librerías externas necesarias
_____________________________

Como la placa ha sido diseñada con el software CADSoft Eagle PCB Design, se han utilizado las siguientes librerías:

- Los diodos schottky de SparkFun-DiscreteSemi https://github.com/sparkfun/SparkFun-Eagle-Libraries
- La shield arduino y xbee de Adafruit https://github.com/adafruit/Adafruit-Eagle-Library