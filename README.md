# JHLidarLite
Interface for PulsedLight, Inc Lidar-Lite to NVIDIA Jetson TK1 Development Kit
http://pulsedlight3d.com

Requires: 

$ sudo apt-get install libi2c-dev i2c-tools

The Lidar-Lite appears as 0x62 on i2c bus 1 on the Jetson TK1 with this wiring:

<blockquote><p>VCC J3A1-1 ->  Lidar-Lite (+)    5V (red wire)<br>
GND J3A1-14 ->  Lidar-Lite (-)<br>
SCL J3A1-18 ->  Lidar-Lite (SCL)<br>
SDA J3A1-20 ->  Lidar-Lite (SDA)</p></blockquote>
