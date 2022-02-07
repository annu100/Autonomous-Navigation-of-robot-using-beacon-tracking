# Autonomous-Navigation-of-robot-using-beacon-tracking

    Initially, ESP32 mounted on the robot will read RSSI (Radio Signal Strength Indicator) levels in forward, right and left direction by suitable in-place rotation.
    Average of 20 RSSI values are taken while measuring RSSI level in a particular direction. This is done in order to read accurate RSSI levels.
    The robot then rotates towards the direction having the highest RSSI level.
    Further, It moves forward with a distance depending on the free space available in front of it. The free space in front of the robot is measured using ultrasonic sensor.
    By repeating above steps again and again, the robot navigates towards the beacon.
