# BandwidthConverter
Author: Daniel Hutama
January 6, 2021

Converts between wavelength and frequency bandwidth with index of refraction considerations. The .exe file can be found in the dist folder.

The .exe file can be used as a stanalone object, but has a significant boot time. However, once it has booted, it can be used repeatedly. If you have a Python IDE, it might be favourable to run the BandwidthConverter.py file, as this is the same program but with boot time limited by the boot time of your IDE.

The program first asks for the index of refraction (e.g. 1.44 for silicon). Following this, the user enters a value in the list [1, 2, 3, 4], which determimes which branch the code executes. Branch 1 converts wavelength (nm) to frequency (THz). Branch 2 converts frequency (THz) to wavelength (nm). Branch 3 converts wavelength bandwidth to frequency bandwidth. Branch 4 converts frequency bandwidth to wavelength bandwidth. The program self repeats until closed by the user. 
