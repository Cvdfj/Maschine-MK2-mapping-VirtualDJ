# Maschine-MK2-mapping-VirtualDJ
Working Maschine MK2 mapping for VirtualDJ

Hi, ive made a mapping of the Maschine MK2 controller. The maschine is a great midi controller and you can get it now very cheap. :)

These are the files contained into the ZIP file:

1.- Folder Controller Editor Template:  
VirtualDJ.ncm2 
You have to install the Controller Editor from N.I. and then import these Template). You have to do this only once. Then its stored into the Maschine MK2 controller.

2.- Folder Devices: 
Maschine MK2 In.PNG 
This is the picture of the maschine when its detected by VirtualDJ. 
Copy this into the APPDATA/local/Virtualdj/Devices folder.

Maschine MK2 In.xml
This is the definition file for the controller (Name, PID, VID, Midi, Leds, etc)
Copy this into the APPDATA/local/Virtualdj/Devices folder.

IMPORTANT: some maschine mk2 controllers have different PID VID. They are not all the same according from what i have read. So, if your maschine its not detected, you can always check this two parameters, and change it on the definition file:

Change in the first  line according to your Maschine MK2. 
vid="0x17CC" pid="0x1140"

3.- Folder Mappers:
Maschine MK2 In.xml
This is the mapping files for the device.
Copy this into the APPDATA/local/Virtualdj/mappers folder.

These mapping controlls almost everything about the sampler. You can sample direct from the maschine, control the sample behaviour (loop, one shot, etc...), it has a volume per sample mapped to the encoders, fx, etc.

Im releasing the mapping as it is, because im making all this stuff from my mixer right now and im gonna sell my maschine very soon :D. Need more space for other hardware. :D.
Feel free to modify or improve it the way you wannt. It would be perfect if experienced mapping users could improve this map and add more functionallity to it.
Feel free to fork.

Cheerios :D

