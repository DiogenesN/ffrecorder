# ffrecorder
A simple audio and screen recorder. It was tested on Debian 13 Stable, on Wayland. There are two modes: Audio and Video, each mode has two more options: recording from the microphone and recording the system sound (sound that comes e,g, from your browsers, players etc.). 

# Installation
  1. Install the following libs:

		 yad
		 sed
		 gawk
		 grep
		 bash
		 ffmpeg
		 coreutils
		 wf-recorder
		 pipewire-pulse
		 pulseaudio-utils

  2. Open a terminal and run:

		 chmod +x ./ffrecorder
		
  3. Copy the script to /usr/local/bin:
  
		 sudo cp ./ffrecorder /usr/local/bin/

  4. Launch the app:

         ffrecorder

# NOTE:
For proper operation, copy this script to /usr/local/bin.

# Screenshots
 ffrecorder window:\
![Alt text](https://raw.githubusercontent.com/DiogenesN/ffrecorder/main/4.png)
 
 Choosing the mode:\
![Alt text](https://raw.githubusercontent.com/DiogenesN/ffrecorder/main/2.png)

 Choosing the source (sources that end in '.monitor' will record the system audio, the rest is mic):\
![Alt text](https://raw.githubusercontent.com/DiogenesN/ffrecorder/main/3.png)

 After clicking on 'Record', this dialog appears where you can 'Stop Recording':\
![Alt text](https://raw.githubusercontent.com/DiogenesN/ffrecorder/main/2.png)

That's it!

# Support

   My Libera IRC support channel: #linuxfriends
   
   Email: nicolas.dio@protonmail.com
