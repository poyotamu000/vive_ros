## How to use command-vive-mode

- set base station
- set head mount display
-- chech red LED in head mout display
-- connect usb, HDMI (display port is unstable) to control PC
- launch
```
roslaunch vive_ros server_vr.launch
roslaunch vive_ros vive.launch
roslaunch vive_ros connect_image.launch (if you want to see the image from Musashi with HMD)
```
- setup robot
- euslisp
```
(command-vive-mode :limb :both :run t)
```

## Button Arrangemnet

- when pushing big circle button, the robot moves.
- when pulling trigger, the hand closes
