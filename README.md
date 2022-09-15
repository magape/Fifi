# Fifi

Fifi (First Fish) is a robotic fish I started to develop in early 2021. The development of Fifi is described in an [article](https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/Fifi_C16-67-84_Ro.pdf) published in 2021.

<img src= https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/3D/img/fifi.png title="Fifi" width=50%>

## Mechanical parts

The mechanical parts are 3D printed using the [stl files](https://github.com/magape/Fifi/tree/main/3D/stl).

<img src=https://github.com/magape/Fifi/blob/c8d3c93399d7731a9bf55d394859fb79013eebce/img/IMG_20210403_213018.jpg title="3D printing parts 1" width=50%>

<img src=https://github.com/magape/Fifi/blob/1faf09c83bfcbcf30c4c174d3087885c5e1e3375/img/IMG_20210404_232729.jpg title="3D printing parts 1" width=50%>

The head, tail actuator, and dorsal actuator are bonded to the fish body with glue. 

The down cover is assembled with two M2 nuts screwed in two M2 inserts attached to the fish body.

<img src=https://github.com/magape/Fifi/blob/71b6a8adc576c3084e7cf7b84f8646a2b4326ab5/img/IMG_20210410_231636.jpg title="Fifi assembled" width=50%>

## Electrical part

The robot is powered by a 2s LiPo battery. 

There are two magnetic actuators which acts the dorsal and caudal fins. 

The actuators are controlled by an Arduino Nano board, via a DRV8838 dual driver module.

For the dry test, the electrical assembly was prototyped on a breadboard.

<img src=https://github.com/magape/Fifi/blob/451dab6ceee6f8d0d2699cd187de2251b30815c9/etc/IMG_20210411_162001.jpg title="Circuit on breadboard" width=50%>

For the wet test, instead of using the breadboard, we soldered the wires to obtain a smaller circuit which could be introduced inside of the fish body.

<img src=https://github.com/magape/Fifi/blob/451dab6ceee6f8d0d2699cd187de2251b30815c9/etc/IMG_20210518_101144.jpg title="Soldered circuit" width=50%>

The underwater simple test showed that Fifi can move straight, up-down and left-right in water.

Unfortunately, the test proved that Fifi is not waterproof.

[![Fifi]<img src=https://github.com/magape/Fifi/blob/8750d0b7597c1b4b8ead5aec5d99545ad5d937d7/img/Youtube_Fifi.png title="Soldered circuit" width=50%>](https://youtu.be/WQkzO7SjSzM)

## Credits

Fifi was designed by [Mihai Agape](https://github.com/magape).

## Licence

[Licensed under the Creative Commons — Attribution-ShareAlike 4.0 International — CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

## Note

This project has been initiated as part of the Erasmus+ project ["New Generation Schools in the Light of Education 4.0"](https://eduplus.ro).

This is a work in progress.

## Disclaimer
The European Commission's support for the project "New Generation Schools in the Light of Education 4.0" does not constitute an endorsement of the contents of this publication, which reflect the views only of the authors, and the Commission cannot be held responsible for any use which may be made of the information contained therein.
