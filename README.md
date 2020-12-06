# Mini FAQ

## I'm only getting the Memory Card/ Music Player screen
- ensure the lid is actually closed (this happens regularly) 
- ensure the FFC is connected correctly 
- ensure the cables are connected as shown in the guide:   
  https://github.com/x-station/xstation-releases/blob/main/xStation_Installation_Guide_english_PU18.pdf
- follow the user guide on how to set up the 00xstation system folder:   
  https://github.com/x-station/xstation-releases/blob/main/xStation_User_Guide.pdf
  
## Games freeze, FMV stutter or stall, audio skips
The xStation needs a well performing SD card that can deliver CD data reliably in under 6.7ms.   
To help the SD card, format it using the official formatter tool. It really helps with access times:   
https://www.sdcard.org/downloads/formatter/   
The tool will automatically choose exFAT (for larger cards) and set correct alignments and cluster sizes.   
If the issue persists:
- try a different SD card to see whether the problem is with the card or the installation
- double check the installation, make sure that the pads below the lifted pins do not make contact
- The lid open/close switch can be worn and barely make continous contact. Try wedging in something that pushes it down properly.   

## xStation can't reset the console, full boot not working, after updates no automatic reset
The most likely cause for reset signal issues is that the QSB reset point doesn't connect well (or at all) to the PSX mainboard.   

![QSB Reset point](https://i.imgur.com/xuve2ri.png)

An alternative test point exists near the expansion port.   

![Reset alternative](https://i.imgur.com/QgGQPQ8.png)

It is okay to solder an additional wire from the QSB to that reset point to fix the issue.

## Test points for PU-18   
Thanks to jft and ryanm101, we now have 2 different test point images. Use them to verify that each signal is soldered down properly.

Variant 1:
![variant1](https://user-images.githubusercontent.com/5185337/100875797-6641d680-349e-11eb-85f8-eb8d9cd4f155.jpg)   

Variant 2:
![variant2](https://i.imgur.com/doQvJGf.jpeg)   


## Test points for LATE PU-8 (-21 and later)
This diagram was made by mmmonkey. 

![Late PU-8](https://i.imgur.com/gTHg3ca.jpeg)   
