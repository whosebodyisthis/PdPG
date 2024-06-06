# PdPG
Pure Data implementation of Curtis Roads' Pulsar Generator

# Dependencies:
Tested on Pd 0.54 (requires the newer file-handling objects)

FluCoMa for Pd (https://learn.flucoma.org/installation/pd/ for installation instructions)

# Getting Started
Open "_PdPG_Main.pd"

Turn up the volume and you should hear sound

Start messing around with sliders

PdPG comes with a folder of wavetables from http://www.adventurekid.se/AKRT,
but you can point PdPG to any folder of wavetables on your computer. Wavetables
should be 16/24 bit and all of the same length (these wavetables are all 600 samples long,
but could be any length).

The "net" buttons in the main panel will train a KNN regressor with five random wavetables
from the collection for "scan" to interpolate across. 

BE WARNED weird things happen when the "net" buttons are pressed whilst the respective 
"scan" is being modulated from the mod windows. If this weird stuff happens (you'll know 
it when you see it), just turn off modulation and hit the "net" button again.

Work in progress
