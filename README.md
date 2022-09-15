# Fifi

Fifi (First Fish) is a robotic fish I started to develop in early 2021. The development of Fifi is described in an [article](https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/Fifi_C16-67-84_Ro.pdf) published in 2021.

<img src= https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/3D/img/fifi.png title="Fifi" width=90%>

## Mechanical parts
The mechanical parts are 3D printed using the [stl files](https://github.com/magape/Fifi/tree/main/3D/stl).

<img src=https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/img/IMG_20210403_213018.jpg title="3D printing parts 1" width=90%>

<img src=https://github.com/magape/Fifi/blob/1faf09c83bfcbcf30c4c174d3087885c5e1e3375/img/IMG_20210404_232729.jpg title="3D printing parts 1" width=90%>

The head, tail actuator, and dorsal actuators are bonded to the fish body with glue. The down cover is assembled with two M2 nuts screwed in two M2 inserts attached to the fish body.

<img src=https://github.com/magape/Fifi/blob/71b6a8adc576c3084e7cf7b84f8646a2b4326ab5/img/IMG_20210410_231636.jpg title="Fifi assembled" width=90%>

## Electrical part

The robot is powered by a 2s LiPo battery. There are two step-down convertors which output the two necessary voltages: 3V convertor (right side) for the microcontroller and 5V convertor (left side) for motors. The two step-down convertors are assembled on two custom PCBs to be easier to mount on the robot chassis. 
The robot has a line sensor mounted on the front of the robot. The board is powered with a 3 V voltage, the same voltage as the microcontroller. Four analog signals are sent from the line sensor to the microcontroller. The line sensor contains four SMD opto-reflective sensors assembled on a custom PCB.

<img src= https://github.com/magape/uBot/blob/f5f0353792feabad80ec027229a1f4c80dda52a6/etc/4LineSnsNoCtrl3V_sch-rgb.png title="Line sensor schematic" width=90%>

<img src= https://github.com/magape/uBot/blob/7714591823c119a591a998ec4e5a49af790a6cc0/etc/4LineSnsNoCtrl3V_3Dbot.png title="Line sensor - bottom" width=90%>

uBot is controlled by a micro:bit board, installed on a micro:bit extension board. The microcontroller receives four analog signals from the line sensor and based on these signals computes the robot position related to the line. 

<img src=https://github.com/magape/uBot/blob/11febca84f6c5f6c41ce262fe1bb5a145891c70a/img/20220703_123827.jpg title="uBot" width=90%>

The microcontroller controls the speeds of the two motors, via a dual motor driver DRV8838 module, using PWM signals.

[![uBot]( https://github.com/magape/uBot/blob/14cb04c93d6d7820f3e731355ba3ac0390ead9fe/img/uBot_YouTube.png)]( https://youtu.be/6SwylmoUkn4)

## Credits

The uBot was designed by [Mihai Agape](https://github.com/magape).

## Licence

[Licensed under the Creative Commons — Attribution-ShareAlike 4.0 International — CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

## Note

This is a work in progress.






# Fifi

Fifi (First Fish) is a robotic fish I started to develop in early 2021. The development of Fifi is described in an [article](https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/Fifi_C16-67-84_Ro.pdf) published in 2021.

<img src= https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/3D/img/fifi.png title="Fifi" width=90%>

## Mechanical parts
The mechanical parts are 3D printed using the [stl files](https://github.com/magape/Fifi/tree/main/3D/stl).

<img src= https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/img/IMG_20210403_213018.jpg title=”3D printing parts 1” width = 90%>

<img src= https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/img/IMG_20210404_232646.jpg title=”3D printing parts 2” width = 90%>

The head, tail actuator, and dorsal actuators are bonded to the fish body with glue. The down cover is assembled with two M2 nuts screwed in two M2 inserts attached to the fish body.

<img src=https://github.com/magape/Fifi/blob/71b6a8adc576c3084e7cf7b84f8646a2b4326ab5/img/IMG_20210410_231636.jpg title="Fifi assembled" width=90%>

## Electrical part

The robot is powered by a 2s LiPo battery. There are two magnetic actuators which acts the dorsal and caudal fins. The actuators are controlled by an Arduino Nano board, via a DRV8838 dual driver module.
For the dry test, the electrical assembly was prototyped on a breadboard.
<img src=https://github.com/magape/Fifi/blob/451dab6ceee6f8d0d2699cd187de2251b30815c9/etc/IMG_20210411_162001.jpg title="Circuit on breadboard" width=90%>

For the wet test, instead of using the breadboard, we soldered the wires to obtain a smaller circuit which could be introduced inside of the fish body.

<img src=https://github.com/magape/Fifi/blob/451dab6ceee6f8d0d2699cd187de2251b30815c9/etc/IMG_20210518_101144.jpg title="Line sensor - bottom" width=90%>

The underwater simple test showed that Fifi can move straight, up-down and left-right in water. Unfortunately, the test proved that Fifi is not waterproof.

[![Fifi]( https://github.com/magape/Fifi/blob/8750d0b7597c1b4b8ead5aec5d99545ad5d937d7/img/Youtube_Fifi.png)](https://youtu.be/WQkzO7SjSzM)

## Credits

Fifi was designed by [Mihai Agape](https://github.com/magape).

## Licence

[Licensed under the Creative Commons — Attribution-ShareAlike 4.0 International — CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

## Note

This project has been initiated as part of the Erasmus+ project ["New Generation Schools in the Light of Education 4.0"](https://eduplus.ro).
This is a work in progress.

## Disclaimer
The European Commission's support for the project "New Generation Schools in the Light of Education 4.0" does not constitute an endorsement of the contents of this publication, which reflect the views only of the authors, and the Commission cannot be held responsible for any use which may be made of the information contained therein.
