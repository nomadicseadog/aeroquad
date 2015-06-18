# AeroQuad - The Open Source Quadcopter #

[![](http://aeroquad.com/images/AQ_Quad.jpg)](http://www.AeroQuad.com)

Check out our main website and forum at http://www.AeroQuad.com<br>
For feature requests or bug reports, please submit them to: <a href='http://aeroquad.atlassian.net'>http://aeroquad.atlassian.net</a>

If you are interested in obtaining the latest and greatest code, please visit our main repository at:<br>
<a href='https://github.com/AeroQuad/AeroQuad'>https://github.com/AeroQuad/AeroQuad</a>

The AeroQuad is an open-source hardware and software project dedicated to the construction of remote controlled four-rotor helicopters, also known as quadcopters or quadrocopters.<br>
<br>
AeroQuad hardware typically consists of an Arduino microcontroller (Mega-2560 or Uno) as the flight controller board, and an AeroQuad shield with various sensors, such as an accelerometer and gyroscope. AeroQuad software, written mostly in C and uploaded to the micro-controller via the Arduino IDE, currently supports Rate (Acrobatic) Mode that uses only the gyroscope for flight assistance, and Attitude (Stable) Mode that use both the gyroscope and accelerometer for auto-leveled flight assist. There are also additional sensors that provide numerous other optional functions, such as heading or altitude hold.<br>
<br>
<h2>Current Features</h2>
<ul><li>Multiple flight configurations are supported<br>
<ul><li>Quad X<br>
</li><li>Quad +<br>
</li><li>Quad Y4<br>
</li><li>Tri<br>
</li><li>Hex X<br>
</li><li>Hex +<br>
</li><li>Hex Y6<br>
</li><li>Octo X<br>
</li><li>Octo +<br>
</li><li>Octo X8<br>
</li></ul></li><li>Multiple flight angle estimation algorithms supported<br>
<ul><li>Improved DCM (best with magnetometer)<br>
</li><li>ARG (best with no magnetometer)<br>
</li><li>MARG (experimental)<br>
</li></ul></li><li>Flight options supported<br>
<ul><li>Heading hold with magnetometer or gyro<br>
</li><li>Altitude hold with barometer<br>
</li><li>Altitude hold with ultrasonic sensor (best for low altitude hold and terrain following)<br>
</li></ul></li><li>Enhanced battery monitoring options<br>
<ul><li>Enable auto descent<br>
</li><li>Specify battery cell count<br>
</li><li>Integration with On Screen Display (OSD)<br>
</li></ul></li><li>Multiple receiver options<br>
<ul><li>6 or 8 channel receivers supported<br>
</li><li>PWM receivers<br>
</li><li>PPM receivers<br>
</li><li>PPM using hardware timer<br>
<ul><li>Specific support for Spektrum, Graupner, Robe, Hitec, Futaba, Hitec, Sanwa & others<br>
</li></ul></li></ul></li><li>Telemetry options<br>
<ul><li>Wireless telemetry on dedicated serial port<br>
</li><li>Open Log binary write<br>
</li></ul></li><li>Camera stabilization support<br>
<ul><li>Dedicated servo channels for roll, pitch, yaw<br>
</li></ul></li><li>Custom OSD support for MAX7456<br>
<ul><li>Specify video standard to use<br>
</li><li>Specify callsign to display<br>
</li><li>Built in attitude indicator<br>
</li><li>Display altitude in feet/meters<br>
</li><li>OSD system which allows remote PID tuning!<br>
</li></ul></li><li>Obstacle avoidance using ultrasonic sensors<br>
</li><li>GPS waypoints</li></ul>

<h2>Planned Features</h2>
<ul><li>Position hold using optical flow and ultrasonic sensors</li></ul>
