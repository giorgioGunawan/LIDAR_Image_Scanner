# LIDAR_Image_Scanner
Welcome to the Image_Scanner_Mechatronic_2

IMPORTANT This is a school project and base code is made by Professor Eduardo Nebot of the Australian Center for Field Robotics (ACFR) and the Faculty of Engineering and IT (FEIT). Modification of code are made by myself and my group. (Matthew Lee, Kimia Nassaj, Marco Salim and Giorgio Gunawan).

Author:
Giorgio Gunawan (grggnwn@gmail.com)
Matthew Davis Lee (leematthew46@gmail.com)

ABOUT The systems used in this project are the 68HCS12 DragonBoard Microcontroller and the Pan and Tilt Unit (PTU) provided to obtain the map and shape of an object located within 0.9 to 1.3 metres away. The 68HCS12 is a microcontroller unit used to undertake several functions that are used in this project, such as supplying a PWM output to the PTU according to a desired value, displaying information from the sensors to the LCDs on the board, obtaining raw data from the sensors in the 10 DOF IMU Module through the I2C bus, and processing information for output.

The PTU is consisted of a 10 DOF IMU with a 3 axis gyroscope (L3G4200D), 3 axis accelerometer (ADXL345) and 3 axis magnetometer (HMC5883L) and a pressure sensor (BMP085), which values can be obtained, processed and calculated to get the orientation (heading and elevation) of the unit. Furthermore, the PTU is also equipped with servo motors that can be controlled to position the unit at an orientation in the range from 20-160 degrees. The PTU is also equipped with a Lidar Light sensor version 2 that provides the range of the object it is pointing to.

The purpose of the system is to use the unit to scan an object and plot its shape, display the distance of the object and orientation of the unit, and calculate the area of the shape based on the measurements obtained.
