This is a arduino based project that allows for now :

- dumping/copying a mifare card (mifare 1k only for now).
- compare keys between a token and a dump (check if keys A and B are same on each sectors).
- can be used as a NFC reader with libnfc (at least with a little patch on libnfc on init).

It uses an Arduino mega, an 4x16 LCD, an SD card, a 4x4 analog Keypad and a PN532 chip linked by SPI to the arduino and use interrupts to communicate.