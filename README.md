# robotic-car-using-arduino-l293d-and-dc-motor
Arduino Uno code for robotic car.
Under Void setup() , we declare the connections and set the baud rate to 9600.

There will be 4 cases under Void loop()
1. L = Left
   Inputs from Digital pins 4 and 5 will be high to Input 1 and Input 2 respectively of the motor driver l293d
2. A = Straight
  Inputs from Digital pins 5 and 3 will be high to Input 2 and Input 4 respectively of the motor driver l293d
3. R = Right
  Inputs from Digital pins 5 and 2 will be high to Input 2 and Input 3 respectively of the motor driver l293d  
4. S = Stop
  All inputs will be low.
