## Arduino Bike Speedometer

This is the simple, Arduino based, bike speedometer. 

A velocity is calculated, whenever a magnet pass near a reed switch, closing the circuit. Then, speed is displayed on LCD in kilometres per hour. When the wheel is still for 2 seconds, the velocity is set to zero. Maximum measurable speed is limited by 100ms debounce time and it equals 76.68 km/s.

The script was prepared specifically for my bike, with 26 inches wheels. Double check the size of your wheels before using it.

<img src="https://github.com/lukkry/speedometer/blob/master/photos/photo_1_min.jpg" alt="Arduino Bike Speedometer" />

### Ingredients
* Arduino Micro
* LCD 8x2, based on the Hitachi HD44780 
* Reed switch
* Magnet (mounted to one of the wheel's spoke)
* 10k ohm resistor
* 50k ohm potentiometer
* Toggle switch x 2
* 9V battery
* Epoxy paper protoboard

### Video
https://www.youtube.com/watch?v=Dy2b9hupqwA

### Credits
Inspired by [Arduino Bike Speedometer](http://www.instructables.com/id/Arduino-Bike-Speedometer)
