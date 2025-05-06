# Photoluminescence Spectrometer GUI

This repository contains the code for the Guided User Interface (GUI) developed for the Photoluminescence Spectrometer @ EuroFEL Support Laboratory (CNR-ISM, Rome). It also includes two executable files:
- One for devices running the **Macintosh** operating system
- One for **Windows** systems
A sample .spc file is also provided to allow testing of the GUI.

## Overview

The GUI allows to generate directly .nxs files from .spc files

### .spc File Output

The `.spc` files are the output of a **Horiba iHR320 - Jobin Yvon** spectrometer. We modified certain parameters in the spectrometer's acquisition software to associate the following metadata dictionary entries with experiment-specific information:
- `PROJECT`: Sample name  
- `SITE`: Temperature at which the experiment was conducted  
- `TITLE`: Title of the experiment

### NeXus Format Integration for Transient Absorption Spectroscopy

A proposed **NeXus file** was also uploaded. This file served as the starting point for modifying the LabVIEW acquisition interface for the Transient Absorption beamline.

## Getting Started

To use the GUI:
1. Download the appropriate executable for your operating system.
2. Download the sample .spc
3. Open the executable and play with its functions!
4. If you are using a different operating system, you can download the code and create a custom executable using PyInstaller.

## Contact

For questions or contributions, feel free to open an issue.


