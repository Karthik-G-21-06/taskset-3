# Read PWM using oscilloscope
## Description
This project is to just read the PWD using Oscilloscope.Pulse width modulation(PWM) is a method of reducing the average power delivered by an electric signal by cutting it into smaller parts.
## Components used
1. Arduino uno
2. Oscilloscope
3. LED
## Working
To make a PWM signalthe output is given using a for loop in which a variable runs from 0 to 255 and back to 0. The output pin in Arduino should be PWM supporting to check if the port support just check if th port number has a '~' before the number.Now just connect an oscillscope to the arduino output pin