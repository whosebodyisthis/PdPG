# PdPG
Pure Data implementation of Curtis Roads' Pulsar Generator

<img width="1000" alt="Screenshot 2024-06-06 at 23 50 51" src="https://github.com/whosebodyisthis/PdPG/assets/133358060/01fd66d3-3272-434f-8f62-c0bd4c3d5547">

# Dependencies:
Tested on Pd 0.54 (requires the newer file-handling objects)

FluCoMa for Pd (https://learn.flucoma.org/installation/pd/ for installation instructions)

# Getting Started
Please use the latest Release .zip. One is optimised for Pd Vanilla UI, the other for PlugData's UI.

Open "_PdPG_Main.pd"

Turn up the volume and you should hear sound

Start messing around with sliders

PdPG comes with a folder of wavetables from http://www.adventurekid.se/AKRT,
but you can point PdPG to any folder of wavetables on your computer using the TABLE button. Wavetables
should be 16/24 bit and all of the same length (these wavetables are all 600 samples long,
but could be any length).

The "net" buttons in the main panel will train a KNN regressor with five random wavetables
from the collection for "scan" to interpolate across. 

Work in progress
