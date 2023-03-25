# Servo-IR-Blaster
My 4th project



This program controls a Servo Motor using the Infrared Remote.

I used the Infrared Remote, module sensor and a Servo all connected to an Arduino Uno.

I only needed these libraries: IRremote and Servo.

After the circuitry was done I need the values of 3 buttons UP to + 30 degrees, DOWN to – 30 degrees and finally VOL- to set Servo to 90 degrees from the IRremote. Here are the values: UP=FF906F, DOWN=FFE01F and VOL-=FFA857. I got the values from the Serial monitor.

Now that I got the values I was able to control the Servo with a variable named IRServoVal.

I had a few trials and errors but I figured it out and it worked out.

It was really fun.
