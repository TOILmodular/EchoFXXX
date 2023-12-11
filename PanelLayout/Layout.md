## Panel Layout for PCB

The panel dimensions provided in the section "Original Design" below are based on my own module build, since I am not following the standard HP (1HP eq. 5.08mm) size. An alternative by building an HP-standard size panel can be found in the section "HP Standard Design" further below.

### Original Design
Coordinates given in the table fit to the layout of components given in the PCBc in folder GerberFiles.
The layout is the same for both versions.

Panel size: 40mm x 128.5mm

The numbers in the table are refering to the numbers in the picture below.
Coordinates origin is the lower left corner of the panel.


| No. | X-coord. [mm] | Y-coord. [mm] | Comment |
| --- | --- | --- | --- |
| 1 | 11 | 105 | Delay Pot |
| 2 | 29 | 105 | Repeat Pot |
| 3 | 11 | 86.6 | Delay CV Jack |
| 4 | 29 | 86.6 | Repeat CV Jack |
| 5 | 11 | 70 | Original Signal Level Pot |
| 6 | 29 | 70 | Echo Signal Level Pot |
| 7 | 29 | 51.6 | Echo Signal Level CV Jack |
| 8 | 11 | 35 | Line/Mic Input Level Switch |
| 9 | 29 | 35 | Input Gain Pot |
| 10 | 11| 15 | Input Jack |
| 11 | 29 | 15 | Output Jack |

<img height="1200" src="https://github.com/TOILmodular/EchoFXXX/assets/97026614/3915abb6-e395-423e-bf56-1d0b9dfc837f">

### HP Standard Design

For building the panel with a size following the HP standard, you can use the panel Gerber file provided in the folder "GerberFiles".
I ordered my own panel via such gerber file built out of PCB material.

Here are a few parameters of the panel.
| Parameter | Value |
| --- | --- |
| Width | 8HP |
| Pot hole diameter | 8mm |
| Jack hole diameter | 6.1mm |
| Toggle switch hole diameter | 6.5 mm |
| Mounting hole diameter | 3.2mm|
