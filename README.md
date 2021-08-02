# KiwiSAT CW Beacon
 KiwiSAT CW Beacon Description and Software

KiwiSAT CW Beacon Telemetry Display Programme.
Documentation:
Version number: v02.0

This document describes the operation of the KiwiSAT CW Beacon Telemetry Display Program.
This program is Freeware, downloadable via internet from KiwiSAT web site and may be distributed freely. It is copyright to AMSAT-ZL and may not be sold or used for any commercial purposes.
Users are encouraged to make a donation to their national AMSAT organisation to help build and maintain Amateur Radio (OSCAR) satellites. 
It has been produced to enable users to manually enter the data from the KiwiSAT CW Beacon and display the telemetry.

For the 1200 bps and 9600 bps data beacons, the program KiwiSAT-TLM should be used.

See www.amsat-zl.org.nz.

This version of the program is a Windows application and will run on the following:
Windows 7 and XP. (It should run on other versions but these have not been tested)
The program has been written in Microsoft Visual Basic Express 2008.
Linux and MAC developers can obtain the Source Code by contacting the author:
zl2bac@amsat.org

We hope to have versions for these operating systems available eventually.

Ground Station Equipment:
KiwiSAT has three beacons and any one may be active depending on the operating schedule.
To receive the KiwiSAT CW Telemetry beacon you will need:
1) A 2M receiver capable of copying CW (Morse Code) transmissions, e.g. "Funcube dongle".
2) A small 2M beam antenna. Gain ~ 6 dBi.  You may be able to receive telemetry with simpler antennas but this would give marginal results.
3) A suitable tracking program.

Installation:
The downloaded zip file (KiwiSAT-CW.zip) contains the program setup file.
Unzip these files into a convenient folder.
Run the setup program and browse to this folder to install the program.
Set up the program bar, desk top and short cuts as desired. 

KiwiSAT-CW Operation:
Start the program.
The starting screen consists of a tool bar and display area.
The tool bar has the following menus:
1) File
2) Help

File:
1) Open > Allows you open a text file, saved from a CW decoding Program, e.g. Fldigi and load it into the Data Entry Input File text box.
2) Paste > Allows you to paste input data from the windows clipboard into the Data Entry Input File text box.
3) Save Input to File > Saves the accumulated manual Data Entry values to a text file.
4) Save Results to File > Saves accumulated results to a text file for both manual and Input File entries.
5) Print Results > Sends the accumulated results to a printer.
6) Exit > Closes the program.

Help:
Opens a window to select this file and an "About KiwiSAT-CW" note.

Running the Program:
If you wish to down load "real time" Telemetry, run your tracking program to determine when a suitable pass is due.
Check the KiwiSAT web page for the current operating schedule to confirm which mode the beacon is set to.

Run KiwiSAT-CW
If the satellite is in view and your radio is tuned correctly then you should hear the Morse code from the CW Beacon.
The data format is: KIWI xxxx yyyy zz a
Where xxxx are the hex numbers for the battery Voltage, yyyy are the hex numbers for the mode, zz are the hex numbers for the last message ID and a is the hex number for the ROM ID.
Enter xxxx into the Data #1 field, YYYY into the Data #2 field, zz into the Data #3 field and a into the Data #4 field.
Click the "Decode" button to display the results.

If you wish to keep the data, then click the "Save Input" button.

If you are decoding data from a file, then use the “Step” button to step through the data frames. 
At the end of the pass, save the using the "Save Results" function on the File menu.

Terry Osborne. (ZL2BAC)

08/04/2017
