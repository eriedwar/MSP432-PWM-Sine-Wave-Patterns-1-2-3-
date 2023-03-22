# MSP432-PWM-Sine-Wave-Patterns-1-2-3-
This code utilizes Port Interrupts and PWM to control the pattern of a Sine Wave using LED's 

This code is written for an MSP microcontroller to control PWM signals to drive LED waves. There are three functions: sineWave, randLEDWave, and noisyWave. In the sineWave function, an array of PWM duty cycle values is used to drive the LED waves. The fillPattern function generates a random array of 20 integers to be used in the randLEDWave function. The noisyWave function uses another pre-defined array of PWM duty cycle values to drive the LED waves. The code also includes global variables that store the PWM duty cycle values for the three LED wave patterns.
