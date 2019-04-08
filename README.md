# utransimpedance
transimpedance amplifier for measuring low currents with a DMM, inspired by the µcurrent of Dave Jones from the EEVBlog.

All files are licenced under Creative Commons - Share Alike 4.0 International (https://creativecommons.org) 

The PCB is designed to be mounted on an aluminium case from Hammond Manufacturing(R) (1550P or 1550PBK)
Battery holder (Keystone 1120C) should be added.

Estimated technical data:
	Ranges:			6, 10^2 to 10^7 V/A
	Minimal Resolution: 	1pA with 5.5 Digit DMM
	Upper Limit:		10mA
	Maximum Input Current:	160mA(continous), 4A (max. 1µs, non repetive)
	Accuracy:		~0.05%
	Offset			< 2µV
	Bandwidth (-6db):	250kHz
	Power Consumption:	10mW (electronic only)
	Battery Lifetime:	100h-400h (LiFeS2-primary cells, depending on measured current)
	Battery low threshold:	2.64V

directory structure:
	Altium		Altium Circuitstudio(R) source files
	Documentation	pdf documents (schematic, BOM)
	Gerber		mechanical files for production
	STEP		3D CAD model

	
