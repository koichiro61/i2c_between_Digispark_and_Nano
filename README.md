# i2c_between_DIgispark_and_Nano

Since USB serial is not available when PB3 and/or PB4 are connected to devices,
you cannot debug sketches by checking values of variables in the sketch with serial monitor
on your PC in this case.
The sketches in this repositry realizes i2c connection between Digispark and Arduino
so that values of variables can be seen from Arduino and be displayed on serial monitor
on your PC via USB serial connection betweeb Arduino and the PC.