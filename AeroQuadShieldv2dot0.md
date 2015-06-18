# AeroQuad Shield v2.0 Capabilities #
Eagle files and PDF's can be found at: http://code.google.com/p/aeroquad/source/browse/#svn/trunk/Documentation/Shield/AeroQuad_v1.7

## External Pilot Commands ##
  * I2C commands received from external daughter board
  * Serial commands received through TX0/RX0 (generated from the Configurator or your own custom program)
  * PPM input on pin 49
## Inertial Measurement Unit ##
  * 6DOF Inertial Measurement Unit constructed of either the
    * Sparkfun 5DOF IMU and IXZ500 Yaw gyro
    * Sparkfun IMU 6DOF Razor
## Motor Control ##
  * 10 non-powered servo style outputs to drive external ESC's using PWM
    * power will be routed to servo outputs
<a href='Hidden comment:   * Screw down terminals for driving I2C ESC"s'></a>
## Servo Control ##
  * Used for camera stabilization and/or tilt, motor tilt or any other deployment
  * 10 powered servo style outputs powered from Motor Control ESC's
    * 4 servos powered from motor output 1
    * 4 servos powered from motor output 2
    * 2 servos powered from motor output 3
<a href='Hidden comment:  * still need to decide how to provide power to servos if I2C used'></a>
## Additional Sensors ##
  * Magnetometer input from HMC5843 via I2C
  * Barometer input from SCP1000 via SPI
  * 4 Proximity sensors using analog input channels (servo style connector)
  * GPS connections for 3.3V and TX1/RX1
    * Additional 5V connector supported through AeroReceiver Board
  * AttoPilot Voltage and Current Sense using an analog input channel (servo style connector)
  * Voltage divider for battery monitor
## Customizable light pattern ##
  * Darlington array drivers for quantity 7 12V LED strips (power directly from external 12V lipo)
## Utilities ##
<a href='Hidden comment:   * Reset button'></a>
  * Ready LED (connected to DIO 13)
  * Spare I2C connection
  * Spare SPI connection