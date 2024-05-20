**JVC SR-S365U controller component for TouchDesigner**

![alt text](https://i.imgur.com/fvHVwEJ.png)

**Features:**
- Direct move to specified timecode (hr/min/sec/frame)
- Transport controls w/status indicators
- Forward/reverse frame advance, variable playback speed
- Contains preconfigured CHOPs for mapping controls to trigger events/events to trigger controls
- Connects via RS-232C connection
- Built in TD 2021.11180




**Usage:**

Import .TOX component into TouchDesigner project for use in projects.
Double-click into component for more 
information on operating the controller.
Debugging available using "serialReply" DAT.
If serial response byte 02h (ERROR) persists, 
the Stop button will send byte 56h (CLEAR) 
to clear the error. If this fails to clear the error, 
disconnect the VCR from power and turn back on.
