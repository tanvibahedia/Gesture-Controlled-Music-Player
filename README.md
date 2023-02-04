# Gesture-Controlled-Music-Player

It is a Player where you can control the music using simple hand gestures for various works, like:

  1.  Volume Up (Left hand distance less than 15cm and more than 10cm)
  2.  Volume Down (Left hand distance less than 40cm and more than 20cm)
  3.  Play/Pause (Both hands on both the sensors within the range of 25-50cm)
  4.  Next (Right hand distance between 0cm to 8cm)
  5.  Rewind (Right hand distance less than 15cm and more than 10cm)
  6.  Forward (Right hand distance less than 40cm and more than 20cm)

Instructions to run:

1. Run the arduino file, Compile it.

2. Connect Ultrasonic Sensors to Arduino at places:
   
   a. Trigger of L-Sensor to 1
   b. Trigger of R-Sensor to 3
   c. Echo of L-Sensor to 2
   d. Echo of R-Sensor to 4
   e. Ground of both the sensors to ground of Arduino
   f. Voltage of both the sensors to 5V of the Arduino 
   
   *NOTE: if the arduino has 1-5V and 1-3.3V, the 5V one would work properly and given priority which will not let one of the sensors work properly.
    
3. Open Python file in any IDE and run the same.
    
    *NOTE: You should check the Ports Arduino is connected to and change the Python Code accordingly.
    a. Serial package
    b. Time package
    c. Pyautogui package
    
 4. Open any Music Player application or Youtube and the following events will happen.
