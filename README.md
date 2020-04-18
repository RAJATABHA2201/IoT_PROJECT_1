# IoT_PROJECT_1
This contains the gas sensor interfacing with real time display
Components used:
TGS 826 gas sensor
Piezo Buzzer(Actuator)
Arduino UNO R3
RTC DS3231(real time clock)

In this project we will be using a gas sensor to detect the amount of gas in the surroundings and it will be read in the serial monitor with time stamp and respective values.

The analog values are converted into its respective ppm values through map function.

The RTC DS3231 is a sensor which gives us real clock time.

In the project the piezo buzzer will be activated while the sensor detects a value>10 ppm,which will it create a buzz sound along with awareness.
