# HRVTool v0.96
## Methods for analyzing Heart Rate Variability

The present functions are made for Matlab R2015a. Errors may occur using older releases (at least R2014b required). Since v0.96 additional toolboxes are not required.

**HRV.m** is a Matlab class containing function for analyzing HRV.
**HRVTool.m** contains the code to start the GUI (Graphical User Interface) on Matlab.
**HRVTool.mlappinstall** is the app package which can be installed with Matlab.

Please run HRVTool.m to start the GUI or click on the icon in the App menu of Matlab.
The user interface has been tested on Windows 7 64bit, Linux Ubuntu 14.04 and Mac OS 10.9.

### Supported files
- [x] Polar hrm files
- [x] mat files containing waveforms or RR intervals (in ms)
- [x] text files containing waveforms or RR intervals (in ms)
- [x] Physionet ecg files if Physionet wfdb toolbox is installed

Other formats are possible to load. Please write an email to marcus.vollmer@uni-greifswald.de


This work and all supported files and functions are licensed under the terms of the MIT License (MIT)
Copyright (c) 2015-2016 Marcus Vollmer

29 June 2016
