# OBS RECORDING NOTIFICATION

A popup window that notifies you when OBS is recording

![alt text](https://raw.githubusercontent.com/tobsailbot/obs_recording_notification/main/Instructions/rec%20timer.PNG)

### How it works:
When the 'Start recording' button is pressed a popup window appears on top of the screen showing you that OBS is recording
You can left-click and drag the window to position it.
This script was made using Python and tkinter library.

### Features:
- The window sticks to the edges of the screen when they are close.
- You can enable or disable the Timer in the properties
- Pause and unpause supported
- The window is always on top (*negative feature: full screen programs are not supported :c )
- Added an option to hide the counter window after 3 seconds of recording.
            
        
### Installation:
- Download the python-3.6.8-embed-amd64.rar that includes a Python compatible package with the necessary libraries.
- Open OBS and go to - Tools - Scripts.
- Configure the Python installation path by selecting the extracted folder.
- Go to Scripts tab, click the + button and add the "obs_recording_notification.py" file.
- Restart OBS and hit Start Recording. 


![alt text](https://raw.githubusercontent.com/tobsailbot/obs_recording_notification/main/Instructions/python%20select.PNG)



## ATTENTION: 
If you find any kind of bug I suggest you reset the program and kill the OBS process from the task manager. Only tested on Windows 
