# PdPG
Pure Data implementation of Curtis Roads' Pulsar Generator

<img width="711" alt="Screenshot 2024-10-19 at 13 00 17" src="https://github.com/user-attachments/assets/72bb55e8-a991-4674-9711-8564b3ded40f">

# Dependencies:
Tested on Pd 0.54 (requires the newer file-handling objects)

FluCoMa for Pd (https://learn.flucoma.org/installation/pd/ for installation instructions)

# Getting Started
Download the latest Release .zip

Download and install the FluCoMa Toolkit for Pure Data from https://www.flucoma.org/download/

Open Pure Data and navigate to the 'Startup' tab in Preferences (CMD/CTRL+,)

Add "fluid_libmanipulation" (without quotations) to libraries to load on start up (Preferences/Startup, 'New' and OK to save settings). 
Should look like the screenshot below.

<img width="610" alt="Screenshot 2024-10-19 at 13 07 45" src="https://github.com/user-attachments/assets/246555e6-d4dd-452d-9105-6b025a73f608">

Close then re-open Pure Data.

Open "_PdPG_Main.pd". 

Turn up the volume and you should hear sound.

# Wavetables
PdPG comes with a folder of wavetables from http://www.adventurekid.se/AKRT,
but you can point PdPG to any folder of wavetables on your computer using the TABLE button. Wavetables
should be 16/24 bit and all of the same length (these wavetables are all 600 samples long,
but could be any length).

Work in progress
