# STM32H7_control-board
Contains the code in STM32CUBEMX format for controlling STM32H753ZI nucleo board
# Prescaler calculations
Sysclk = 64MHz <br />
PWM Freq = 1kHz <br />
Timer freq = 256kHz  <br />
## Formulas 
Prescaler = (System Clock/ Desired Timer freq) -1 <br />
Prescaler = 249 <br />
Period = 255 <br />
