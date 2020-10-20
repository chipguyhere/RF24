
# chipguyhere's fork of nRF24/RF24

This fork is to publish a few tweaks I have needed to make to the RF24 library to get them to work in my projects.  Specifically:
* I need to be able to lower the SPI clock to work with a popular clone for sale on Amazon
* I need to be able to neutralize PROGMEM/F() to get this code to work with megaAVR/Arduino Nano Every.

## Original documentation:

See http://tmrh20.github.io/RF24 for all documentation
