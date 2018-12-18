# LowPower-Arduino
To Maximize the battery life & to reduce the power consumtpion by Arduino we need to shut down few peripherals which we do not require for the current program.
The Arduino UNO board will draw minimum of 15mA of current , we can reduce that current to 10uA by using this Low Power Mode.
We can achieve this in many ways :
1.Removing Extra Hardware
2.Reducing the clock speed
3.Ditching the voltage regulator
4.Saving power with sofware
Here I am going to explain how to save power with software.

