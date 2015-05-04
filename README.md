# JHLidarLite
Interface for PulsedLight, Inc Lidar-Lite to NVIDIA Jetson TK1 Development Kit
http://pulsedlight3d.com

Requires: 

$ sudo apt-get install libi2c-dev i2c-tools

Here's the wiring on the Jetson TK1 for the test case: 

Appears as 0x6b on i2c bus 1 

<blockquote><p>VCC J3A1-1  (+)    5V<br>
GND J3A1-14 (-)<br>
SCL J3A1-18 (C)<br>
SDA J3A1-20 (D)</p></blockquote>
