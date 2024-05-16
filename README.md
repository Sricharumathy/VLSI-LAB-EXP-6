# SCHEMATIC AND SIMULATION OF CMOS INVERTER USING CADENCE VIRTUOSO

## AIM: 
   To Schematic and Simulate Inverter using CADENCE virtuoso. 
## APPARATUS REQUIRED: 
   CADENCE VIRTUOSO 
## PROCEDURE: 
### Procedure for Commands to get into Cadence<br>
1.	Right Click and open the terminal window<br>
2.	Type the following commands as follows and press enter.<br>
    i)	tcsh<br>
    ii)	source /home/install/cshrc<br>
    iii)	virtuoso <br>
### Procedure for Schematic simulation using Cadence<br>
1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…"<br>
2.	Close the 2nd window<br>
3.	Use 1st window i.e virtuoso window(CIW) for further processing.<br>
i)	Create a New Library<br>
ii)	Create Schematic Cell view.<br>
iii)	Create the Symbol for schematic Cell view.<br>
iv)	Create the test Cell view.<br>
v)	Analog simulation by spectre<br>
### Procedure for Creating New Library.<br>
a)	File –New – Library<br>
b)	Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK<br>
c)	Attach the library to the technology library gpdk045.Click OK<br>
### Create Schematic Cell view.
a)	Go to 1st window i.e virtuoso(CIW)<br>
b)	File-New-Cell view<br>
c)	Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic<br>
d)	Type: Schematic press OK<br>
e)	Add the required components from the libraries and make the connections.<br>
f)	Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos<br>
g)	Analog library	Vdd, Gnd, Vcc, Vpulse, Vsin<br>
h)	Make the connections by using fixed narrow wire key<br>
i)	Click Check and Save button<br>
### Creating the Symbol for schematic Cell view
a.	In the schematic window, execute
Crate – Cell view – From Cell view
The cell view from cell view window appears
Check Lib Name, Cell Name, From View name must be schematic Press ok<br>
b.	Now Symbol generation form appears. Click Ok If No changes required<br>
c.	A new window with with default symbol is created.<br>
d.	Edit the symbol if you want to give actual symbol shape else continue.<br>
    i.	Execute Create-Cell view-from cell view<br>
    ii.	Library Name and Cell Name must be same which you have used for schematic. Press OK<br>
    iii.	Check for the position of pin side.Prss OK<br>
    iv.	Edit for the shape by Create-Shape-Choose required options to edit.<br>
## Creating the new test cell view<br>
a)	Go to CIW window, Execute File-New-Cell view<br>
b)	Setup the new file form<br>
Library: Select the one you a created.<br>
Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test<br>
View: Schematic<br>
Type: Schematic  press OK<br>
Analog simulation by SPECTRE.<br>
a.	In test cell view window<br>
b.	Launch – ADE L(Analog Design Environment)<br>
c.	Execute Setup—Simulation/directory/Host A new window opens<br>
d.	Set the simulation window to spectre and click ok<br>
e.	Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK.<br>
f.	Execute Analysis – Choose. A window opens.<br>
g.	Select the type and set the specifications and press OK<br>
h.	Execute Output s—to be plotted – Select on Schematic<br>
i.	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse<br>
j.	Execute Simulation -- Net list and Run<br>
## Simulation Settings<br>
Setup for transient analysis:<br>
1.	Stop time =400n<br>
Setup for D.C analysis<br>
1.	Component to be selected in schematic is	for d.c analysis<br>
2.	Start = -1 Stop = 1 resp.<br>

## CMOS INVERTER
![WhatsApp Image 2024-05-05 at 11 03 01 PM (1)](https://github.com/Sricharumathy/VLSI-LAB-EXP-6/assets/159044760/ada8a816-eeeb-4a7c-a170-00a44adfff79)
![WhatsApp Image 2024-05-05 at 11 03 01 PM](https://github.com/Sricharumathy/VLSI-LAB-EXP-6/assets/159044760/cb562e23-d165-40d8-9f01-a5ced71df7b8)
### Specifications:
Vpulse 	V1 = 0 ;	V2 = 1<br>
Vdc=1<br>
td = 0,tr=tf=1 n, ton= 100n ,T=200n<br>
## OUTPUT
![WhatsApp Image 2024-05-05 at 11 03 01 PM (2)](https://github.com/Sricharumathy/VLSI-LAB-EXP-6/assets/159044760/94659468-32bc-4e04-97c7-e62901079e98)
## NANDGATE
![WhatsApp Image 2024-05-13 at 9 16 34 AM](https://github.com/Sricharumathy/VLSI-LAB-EXP-6/assets/159044760/35c276ea-ab90-4918-b30c-238c59a27c43)
![WhatsApp Image 2024-05-05 at 11 03 08 PM](https://github.com/Sricharumathy/VLSI-LAB-EXP-6/assets/159044760/3ce118d9-70f4-4b86-a9ee-2959df2f50e2)
### Specifications:
Vpulse A:V1 = 0 ;	V2 = 1<br>
Vpulse B:V1 = 0 ; V2 = 1<br>
Vdc=1<br>
td = 0,tr=tf=1 n, ton= 100n ,T=200n<br>
## OUTPUT
![WhatsApp Image 2024-05-05 at 11 03 09 PM (1)](https://github.com/Sricharumathy/VLSI-LAB-EXP-6/assets/159044760/1838d18b-94d7-4360-b526-58ab923cd972)
## NORGATE
![Screenshot 2024-05-07 145441](https://github.com/Sricharumathy/VLSI-LAB-EXP-6/assets/159044760/a2dc644a-212d-48ce-a99f-e95a0bc4a1c6)
![Screenshot 2024-05-07 145429](https://github.com/Sricharumathy/VLSI-LAB-EXP-6/assets/159044760/9164cf17-408b-4441-9062-13859c20a6b3)
### Specifications:
Vpulse A:V1 = 0 ;	V2 = 1<br>
Vpulse B:V1 = 0 ; V2 = 1<br>
Vdc=1<br>
td = 0,tr=tf=1 n, ton= 100n ,T=200n<br>
## OUTPUT
![WhatsApp Image 2024-05-05 at 11 03 09 PM (2)](https://github.com/Sricharumathy/VLSI-LAB-EXP-6/assets/159044760/3caac581-7b26-4528-b8ca-174761ccfe31)
## RESULT
The schematic and simulate inverter using CADENCE is done and  verified successfully.




