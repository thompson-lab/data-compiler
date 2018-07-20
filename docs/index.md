---
title: Data Compiler
---
# About
The compiler takes in exported data from a spectrometer, especially if after an episodic capture, and combines all files into one spreadsheet.

## Supported Devices
Every device exports data slightly differently, so not everything will work yet. You can see what devices are supported [here](https://github.com/thompson-lab/data-compiler#readme).

# Usage
Using the program is quite simple, but here are in-depth instructions that will hopefully answer your questions.

1. Make sure all of your data files are in the same folder, and that there are no other files in that folder. If this is not the case, make a new folder and put only the data files in it.
2. Inside Data Compiler, click on the folder icon, and select the folder that contains the data files.
3. The software gives each data file a relative time (time passed between capturing the first file and each file thereafter.) It also lets you choose the units to display that time in. Here are the options:
    - __SMART:__ Choose the units dynamically based on how long the time is. Units will be uniform across all columns.
    - __Seconds/Minutes/Hours:__ Display this unit.
    - __All:__ Create a row for seconds, minutes, and hours.
4. Click Go. A prompt will appear allowing you to save the spreadsheet. You may name it whatever you like, but *it must end in `.csv`.*

# Installation
Here are in-depth instructions to install the software.

> **NOTE:** Data Compiler is currently only available on Windows.

> **NOTE:** Data Compiler is powered by LabView 2017, so you'll need the LabView runtime environment to run the software. This is bundled into the installers, so all you need to do is download the correct file for your computer.

1. Right-click the Start button, and click "System".
2. You'll see a screen pop up like this. The bit information is underlined in red.
![windows system page](https://i.imgur.com/Q0uFEDU.png)
3. Go to the [releases page](https://github.com/thompson-lab/data-compiler/releases) and select the installer with the bit number you saw in step 2.
![releases page](https://i.imgur.com/7Tkwu1w.png)
4. Run the installer. At some point, you will see a window like this appear. Click OK.
    ![labview 1](https://i.imgur.com/EfiVMjZ.png)
    
    Then, you'll see this window; click Unzip.
    
    ![labview 2](https://i.imgur.com/6YrC5T9.png)
    
    At that point, the installation will continue, but a LabView installer will also open. **Do not open the Data Compiler software until the LabView installer has completed.**
5. Restart your computer.
5. Once the run-time is properly installed (the LabView installer closes), you can open Data Compiler and use it.

