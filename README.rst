km_dolly - ROS package for KM-1 Dolly Kit
=========================================
Requirements
-----------
pykeigan_motor v2(Python 2 and Python 3 compatible ver.)

https://github.com/keigan-motor/pykeigan_motor/tree/dev

How to use
-----------
::

  cd ~/catkin_ws/src/
  git clone https://github.com/wingcloud/km_dolly
  cd ~/catkin_ws/
  catkin_make
  roslaunch km_dolly km_control.launch connect_mode:=ble right_w_addr:=XX:XX:XX:XX:XX:XX left_w_addr:=XX:XX:XX:XX:XX:XX
