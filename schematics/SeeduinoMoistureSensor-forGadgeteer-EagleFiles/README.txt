Basically this is a gadgeteer compatible module (uses this 10-pin connector).
I've made it usable under arduino, the schematics from Seeduino guys are weird because they reported SIG_IN and SIG_OUT flipped (at least in my logic).
I've simple flipped them and renamed it to SIG_IN_REAL and SIG_OUT_REAL

The sensor will act like: http://www.seeedstudio.com/wiki/Grove_-_Moisture_Sensor
After you've connected the pins to the right place :) (and send a +5v on the SIG_INPUT_REAL)

It works.

