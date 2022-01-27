# TP32
## Tp32 keyboard with running QMK

---

### IMG
[images](img/)

![01](img/01.jpg)
![05](img/05.jpg)
![02](img/02.jpg)
![03](img/03.jpg)

### TrackPoint

for thinkpad t400 r400 t500 r500 .......

![thinkpad](img/thinkpad.jpg)
![tp_1](img/tp_1.jpg)
![tp_2](img/tp_2.jpg)

line    | pad
--------|----------
red     | vcc
black   | gnd
yellow  | clk
green   | rst
blue    | data


### PCB

[gerber](gerber/)

[sch](sch/)

[OSHW](https://oshwhub.com/pkerr/keyborard-juk-32-rev-a)

![pcb_top](img/pcb_top.png)
![pcb_bottom](img/pcb_bottom.png)

### 3D files

[stl](stl/)

[solidworks](sw/)

### qmk

[code](code/)

### bom

Part            | Value     | Quantity
----------------|-----------|-----------
atmega32u4      | au        | 1
trackpoint      |           | 1
ws2812b         | 3528      | 32
1n4148          |           | 32
kaihua choc     |           | 32
usb-c           | 16p       | 1
max 1.25        | smd       | 1
crystal 3225    | 16Mhz     | 1
c 0603          | 22p       | 2
c 0603          | 0.1u      | 8
c 0603          | 1u        | 5
r 0603          | 22        | 2
r 0603          | 1k        | 3
r 0603          | 4k7       | 2
r 0603          | 5k1       | 2
r 0603          | 10k       | 3
sw 4x4          |           | 0 or 1



