*********
RoverWing
*********


Introduction
============
RoverWing is a  shield (or "wing", following Adafruit's terminology) for Adafruit's `Feather boards <https://www.adafruit.com/feather>`_. 
The Roverwing is designed to provide a low cost expansion board for feather boards that allows you to easily build and program simple robots. One can build a simple robot using a roverwing in about 15 minutes as is shown in our `quick start guide <https://github.com/roverwing/RoverWingLibrary/wiki/6.-Building-a-Basic-Robot>`_
This wing provides motor drivers, Inertial Motion Unit (IMU), and connection ports for servos, sonars, GPS, 
and other peripherals commonly used by mobile robots. It also contains a microcontroller preloaded with firmware 
to control these peripherals, which communicates with the Feather board using I2C protocol, thus the freeing resources 
of the Feather board for other purposes. 

The RoverWing was heavily influenced by Adafruit's `CRICKIT <https://www.adafruit.com/crickit>`_   board (in particular, it has exact same dimensions and 
mounting holes as the CRICKIT board). However, unlike CRICKIT, it is intended for use with more powerful 12V motors 
and provides a slightly different set of peripherals. The roverwing allows the user to have finer control over motors due to the ability to attach encoders to monitor each motor. The inclusion of breakouts for connecting to sonar sensors provides an advantage over the crickit board because it allows the user to build robots that can collect more information about their surroundings as opposed to the cricket board which does not support any sensors that allow the robot to gather information about its surroundings. The roverwing is more oriented towards the creation of small autonomous robots as opposed to the circkit's focus on stationary devices that interact with a user.
Below is the list of key features of the RoverWing:

* Can be powered by 7-14V power source; contains a voltage regulator providing power to the Feather board

* Communicates with the Feather board over I2C. 

* Contains on-board microcontroller, which takes care of low-level operations such as counting motor encoder pulses, using preloaded firmware

* Contains on-board 6DOF  Inertial Motion Unit (IMU), based on MPU6050 chip, which can be used for tracking robot orientation in space

* Provides the hardware and firmware support for connecting the following external peripherals

  - Motors: two brushed DC motors, at up to 2.9A at 14V per motor
  - Quadrature encoders for each motor
  - Sonars: support for three HC-SR04 or compatible ultrasonic sensors (sonars)  
  - Servos: four servos (5V) (see note on power limit below)
  - Six analog inputs (3.3V)
  - Neopixel smart LED (see note on power limit below)
  - GPS and magnetometer (compass) sensors
  - two additional I2C sensors
  

The RoverWing uses same connectors for the power supply, motors, encoders, and I2C sensors as the `REV Robotics Expansion hub <http://www.revrobotics.com/rev-31-1153/>`_ 
used in `First Tech Challenge <https://www.firstinspires.org/robotics/ftc>`_  robotics competition, so it can be easily used with the same motors and sensors. 
  
`Hardware Details <https://roverwing.github.io/RoverWingHardware/>`_

`User Library <https://roverwing.github.io/RoverWingLibrary/>`_

`Firmware <https://roverwing.github.io/RoverWingFirmware/>`_

License
=======


