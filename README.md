
# chipguyhere's fork of nRF24/RF24

This fork is to publish a few tweaks I have needed to make to the RF24 library to get them to work in my projects.  Specifically:
* I need to be able to lower/override the SPI clock speed to work with a popular clone for sale on Amazon
* I need to be able to neutralize PROGMEM/F() to get this code to work with megaAVR/Arduino Nano Every.
* I chose to replace printf in my fork to lower the memory footprint for AVR Arduinos

## Original documentation:

See http://tmrh20.github.io/RF24 for all original documentation
