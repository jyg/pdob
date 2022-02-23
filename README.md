# STAGE : multitouch browser-based GUI for PureData
Controlling PureData patches from browser with [Open Stage Control](https://openstagecontrol.ammd.net/) server.
![image](https://user-images.githubusercontent.com/1431894/154551869-8065fbe2-da76-4f52-9215-c1da3cfe7fc4.png)

**STAGE** is a series of abstractions for quickly creating an **OpenStageControl** .json file with GUI elements exported from an existing **PureData patch**. 

Once created, the script has to be executed by the OpenStageControl server, and enables the control of the PureData patch from a **browser-based client interface**, such as Chrome, Firefox, on any target platform (desktop, IPad, Android), via local networking.

## Requirements
* pd > 0.52
* iemguts externals lib

## Current supported and exported widgets :
* hsl / vsl
* bng
* tgl
* hradio / vradio
* comment
* array
* mob/lcd 
