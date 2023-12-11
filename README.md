# EchoFXXX - PT2399 Delay Effect Eurorack Module
Based on the EchoFXXX delay module from Music From Outer Space.

<img height="500" src="https://github.com/TOILmodular/TidesV2/assets/97026614/c0b4c7c7-85f1-46f6-b974-7e1e667eeeb5">
<img height="500" src="https://github.com/TOILmodular/TidesV2/assets/97026614/fd856697-6952-490b-a04d-16914f8106da">

<img height="500" src="https://github.com/TOILmodular/TidesV2/assets/97026614/98aa8a37-630a-4bee-9c60-fc975febbcc0">
<img height="500" src="https://github.com/TOILmodular/TidesV2/assets/97026614/9bd5a2fb-d60d-4abb-80f5-47b4a6b2f0dd">

## Module Build and PCBs
In the folder GerberFiles, I added two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available for me at a local electronics shop.

<img height="500" alt="CtrlPCB_Orig" src="https://github.com/TOILmodular/TidesV2/assets/97026614/bb77a257-724f-46c4-b2ed-661e228c8583">

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created another control board PCB version, called "Thonk", with footprints for those components.

<img height="500" alt="CtrlPCB_Thonk" src="https://github.com/TOILmodular/TidesV2/assets/97026614/49be10a0-fc68-45bf-bac4-b94e0918cb3e">

The main board PCB is the same for both versions

<img height="500" alt="MainPCB" src="https://github.com/TOILmodular/TidesV2/assets/97026614/7f55dded-c53c-4096-819c-0d1c7d66c15c">

I created the Gerber files with the online tool EasyEDA and ordered it at JLCPCB.

## Panel Layout
I added the information about hole coordinates for the front panel in the folder PanelLayout, referring to the component layout in the Gerber files. The layout is the same for all PCB versions.

In addition, there is a Gerber file for the panel, following the HP standard. My own modules do not follow that width standard, as I am only using sliding nuts in my racks.

You can use the panel Gerber file to have the panel built out of PCB material.

## Additional Information about specific Components
The module build requires the soldering of SMD components. Besides the STM32F373 microcontroller, there is the DAC8164 chip and several other components, like op amps, voltage regulators, ceramic capacitors, ferrite beads, and a diode array.

Here is a list of SMD parts in my design.
- STM32F373CCT6 (microcontroller)
- DAC8164 (digital-analog0converter, 16-TSSOP package)
- TLV4172 (quad op amp, 14-SOIC)
- LM1117-3.3 (voltage regulator, SOT-223 package)
- LM4040B10 (voltage regulator, SOT-23-3 package)
- BAT54ST (diode array, SOT-523 package)
- 0.1uF capacitors (1608 package)
- BLM18R (ferrite bead, 1608 package)

Concerning the resistor size, I am usually using small-size resistors, about half the length of the usual size, so they need less space on the PCB. If you want to use my Gerber files, you have to consider that fact. You might still use normal size resistors and put them in a standing position on the boards. Should also work fine.
