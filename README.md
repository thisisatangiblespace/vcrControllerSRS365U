**JVC SR-S365U Controller Component for TouchDesigner**

![alt text]([https://i.imgur.com/qNw0nAX.png])

**Features:**
- Direct move to specified timecode (hr/min/sec/frame)
- Transport controls w/status indicators
- Forward/reverse frame advance, variable playback speed
- Contains custom COMP menu for mapping controls to trigger events/events to trigger controls
- Connects via RS-232C serial bus
- Indicator light glow/flicker effect
- Textured buttons
- If you were to eat the component it would taste like blue raspberry candy
- Tested and working on latest TD 2023.11760 builds for both MacOS and Windows




**Usage:**

Import .TOX component into TouchDesigner project for use in projects.
Double-click into component for more 
information on operating the controller.
Debugging available using "serialReply" DAT.
If serial response byte 02h (ERROR) persists, 
the Stop button will send byte 56h (CLEAR) 
to clear the error. If this fails to clear the error, 
disconnect the VCR from power and turn back on.

*© 2024 Grant Johnson*
*Copyright (c) 2020, keshikan (https://www.keshikan.net),
with Reserved Font Name "DSEG".*
*Copyright (c) 2014 Riciery Leal*
