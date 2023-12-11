# Teleoperate-a-Robot-Using-Hand-Gestures

Gesture-based teleoperation project for a ROS-based robot.
We used an IMU to detect gestures and interfaced with the Arduino to get the values from
the IMU. The Arduino is interfaced with ROS using the ROS serial protocol. The PC is
running a ROS node that can convert IMU orientation into linear and angular velocity and
send it as a twist message. This twist message can be used in any robot just by changing the
teleop topic name. We can also visualize the IMU orientation data in Rviz using TF data
from Arduino. If it is too difficult to build this circuit, we can use an Android app called
ROS Control that can move the robot using the inbuilt IMU on the phone.
