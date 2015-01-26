# avr-millis-function
Just like the millis() function in Arduino, this function returns 
the time in milliseconds since the program started.

This function has only been tested on the atmega328p, but may work on many other AVRs as well.

Implementing this function is easy - take a look at the example:

1) First you must initiate the clock with init_millis()

2) After calling init_millis(), call sei() to enable global interrupts

3) Use millis() whenever you like to get the time in milliseconds since the program started

For any questions write me an email at: contact@monoclecat.de
