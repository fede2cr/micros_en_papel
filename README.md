# micros_en_papel
Creando microcontroladoras en papel

# For english go [here](https://github.com/fede2cr/micros_en_papel/blob/master/README.en.md)

![Prototipo](https://github.com/fede2cr/micros_en_papel/blob/master/doc/img/prototipos/prototipo.gif)

## Descripción

Para fines educativos se quiere que cualquier persona pueda crear una tarjeta similar a un Arduino, sin necesidad de utilizar químicos peligrosos, maquinaria especializada y que pueda ser diseñado y ensamblado en aprox 20 minutos para poder crear talleres de una sola sesión. Así mismo es importante que los materiales sean de muy bajo costo para que puedan ser utilizados de forma masiva.

Se propone inicialmente utilizar un Arduino UNO sin procesador, en lugar de un convertidor serial como un cable FTDI.

## Materiales disponibles

* Papel, cartón o [cualquier otro sustrato similar](https://www.amazon.com/Paper-High-Elephant-Notebook-Large/dp/B00512F4NU/ref=sr_1_27?ie=UTF8&qid=1488605679&sr=8-27)
* [Cinta de transferencia para electrónicos](https://www.amazon.com/dp/B00HDDRUIM/ref=wl_it_dp_o_pC_nS_ttl?_encoding=UTF8&colid=3C30BG4N9HBTS&coliid=I100AKWQFII0SL&psc=1) ["Z-Axis tape"](https://www.adafruit.com/products/1656) o similar
* [Cinta de cobre, con goma conductiva](http://www.crcibernetica.com/copper-tape-5mm-50ft/)
* Lapicero de tinta conductiva [Circuit Scribe](https://www.amazon.com/gp/product/B00OZATJ3A/ref=oh_aui_detailpage_o05_s00?ie=UTF8&psc=1)
* 16Mhz [Crystal kit](http://www.crcibernetica.com/crystal-kit-for-arduino-on-a-breadboard/) con capacitores
* Chip [ATMega328 con bootloader de Arduino UNO](http://www.crcibernetica.com/atmega328-microcontroller-bootloader-uno/) o un [ATtiny85](http://www.crcibernetica.com/avr-8-pin-20mhz-8k-4a-d-attiny85/)

## Retos

- [x] Poder crear circuitos con trazas que brinquen unas encima de otras: Se crea una línea de tierra bajo el chip AVR la cual distribuye del centro hacia afuera, y una línea de 5V del exterior del circuito hacia donde se necesita.
- [ ] Ensamblar sin necesidad de soldadura: Es posible usar algo como cables con terminal de lagarto soldados a cinta de cobre si fuera necesario reutilizar una demostración para varios eventos, pero los estudiantes deben poder completar sus diseños sin necesidad de solar en el taller, abriendo las posibilidades de las instalaciones físicas a desarrollar el taller. Para esto se pretende usar la conocida como "Z Axis Tape" la cual se especializa en pasar la prueba de conductividad en su eje Z (en ambos lados de la cinta) por lo que es utilizado para instalar componentes de tipo SMD en tarjetas sin necesidad de usar una pistola de aire caliente.

### Materiales de referencia
* Tutorial [Arduino to breadboard](https://www.arduino.cc/en/Tutorial/ArduinoToBreadboard)
* Tutorial [Arduino to breadboard - Standalone](https://www.arduino.cc/en/Main/Standalone)
