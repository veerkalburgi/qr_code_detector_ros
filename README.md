# qr_code_detector_ros
QR code detection using OpenCV and ROS

---

1.The QR codes detector based on zbar library (http://zbar.sourceforge.net), dedicated to ROS systems.

2.Installation of zbar library on Ubuntu
`sudo apt install libzbar-dev`

3.Subscribes:
- **/image** (sensor_msgs/Image) - the topic with RGB images which contains QR codes.

4.Publishes:
- **/qr_codes** (std_msgs/String) - message from each detected QR code is published as a string.
