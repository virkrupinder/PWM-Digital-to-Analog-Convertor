# PWM-Digital-to-Analog-Convertor

This is a design of a Pulse Width Modulated (PWM) Digital to Analog Convertor (DAC) built using Python and LTspice. The DAC converts an input of a pulse width
modulated signal into a linear output voltage signal by iltering out all the higher frequencies of the PWM signal and pass through only the DC component of the signal. A 4th order Butterworth Low Pass filter was used for the project. The PWM signal used as an input to the filter has a frequency, fPWM, of 67.12kHz and the cutoff frequency, fc, of the filter was found to be 10kHz. The peak-to-peak ripple voltage of the filter using a 50% duty cycle square wave was found to be and from there the number of effective bits of the filter was determined to be 7.6. 
