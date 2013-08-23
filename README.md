Just an Xcode project that I use in my workflow in editing openFrameworks projects on the Raspberry Pi. 
This will not compile the project. I use the Terminal and SSH to compile and run. This is just a cheap way of getting autocompletion

To use   
On the Raspberry PI:   
Download openFrameworks and put in `/home/pi/openFrameworks`   
http://www.openframeworks.cc/setup/raspberrypi/Raspberry-Pi-Getting-Started.html

Set up Samba(SMB) sharing according to these instructions   
http://www.openframeworks.cc/setup/raspberrypi/Raspberry-Pi-SMB.html

Mount the Raspberry Pi over SMB   
Finder->Connect to Server->smb://raspberrypi.local

Open up Xcode and edit :)

I often add my own project's source code by creating groups and dragging the src folders over from the Finder. Unchecking "add to target" seems to make it faster.




