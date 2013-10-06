SharIR_stm32f0
==============

Testing about Sharp Ir sensor by STM32F0 microcontroller


I will not upload the ST official firmware since it is too much, but i will post the main thing I was implementing.

The pin connection you can see very clearly from the init function.

Notice: I found that using Microlib and Printf will get confict to LCD display. That really has a different implementation 

of serial output using a little bit ST firware's function.
