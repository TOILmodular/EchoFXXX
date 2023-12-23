# EchoFXXX - PT2399 Delay Effect Eurorack Module
Analog Eurorack delay module with a number of control parameters, like input level selection (mic or line/modular), input gain control, CVs for echo signal level, delay time and feedback. Based on the [EchoFXXX delay module from Music From Outer Space](https://musicfromouterspace.com/analogsynth_new/ECHOFXXX/ECHOFXXX.php).

You can check out some sound demo in my [YouTube video](https://youtu.be/SG4Jhu9ZlaE).

<img height="500" src="https://github.com/TOILmodular/EchoFXXX/assets/97026614/3aa597ed-c58f-4af6-9a77-ec9190a18ea0"><img height="500" src="https://github.com/TOILmodular/EchoFXXX/assets/97026614/6d99d3d5-2233-4858-918e-e4b47890b0b5">

<img height="500" src="https://github.com/TOILmodular/EchoFXXX/assets/97026614/30497500-dbcc-47c4-8a7d-d7b80ad9628d"><img height="500" src="https://github.com/TOILmodular/EchoFXXX/assets/97026614/93ec08e5-4f7b-4849-83f1-1be08761d4e5">

## Module Build and PCBs
In the folder GerberFiles, I added two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available for me at a local electronics shop.

<img height="500" alt="CtrlPCB_Orig" src="https://github.com/TOILmodular/EchoFXXX/assets/97026614/b1942de7-1ec2-4fbb-8aca-0c8f0a2cc730">

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created another control board PCB version, called "Thonk", with footprints for those components.

<img height="500" alt="CtrlPCB_Thonk" src="https://github.com/TOILmodular/EchoFXXX/assets/97026614/9e35445f-8500-470b-8893-2b843a64b7c8">

The main board PCB is the same for both versions.

<img height="500" alt="MainPCB" src="https://github.com/TOILmodular/EchoFXXX/assets/97026614/5c47d5a0-aea7-4125-a4cf-9dec6f7e441e">

I created the Gerber files with the online tool EasyEDA and ordered it at JLCPCB.

## Panel Layout
I added the information about hole coordinates for the front panel in the folder PanelLayout, referring to the component layout in the Gerber files. The layout is the same for all PCB versions.

In addition, there is a Gerber file for the panel, following the HP standard. My own modules do not follow that width standard, as I am only using sliding nuts in my racks.

You can use the panel Gerber file to have the panel built out of PCB material.

## Additional Information about Components
The module design is one of my earlier ones, before I started integrating SMD components. So the entire build is through-hole.

Concerning the resistor size, I am usually using small-size resistors, about half the length of the usual size, so they need less space on the PCB. If you want to use my Gerber files, you have to consider that fact. You might still use normal size resistors and put them in a standing position on the boards. Should also work fine.

On the control board, you will find electrolytic capacitors with a rectangle next to them. Since these capacitors are too tall for standing upright on the board with the main board on top of it, those capacitors need to be mounted in a rectangular position. The rectangle shows the position for each bent-over capacitor.

<img height="300" src="https://github.com/TOILmodular/EchoFXXX/assets/97026614/bc37a003-0321-497f-b727-cd78ab788256">
