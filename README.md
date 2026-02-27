# youtube-downloader
This is a YouTube Downloader Tool for Termux in Android Only.
To get started, go to releases and Download the latest zip file. Extract it.
It can also download videos from instagram, tik tok, etc.

==================================

Note: Use Zarchiever App for better experience. Make sure to enable "Show hidden Files"

**Some common things**

If the terminal writes "```Do you want to continue? [Y/n]```" , then simply write "```y```" (small lettered) and press enter.
Your downloaded videos or audios will be saved in Your Download folder in Internal Storage.

--------------------------

• Extract "```yt.zip```". You'll get a folder "```.yt```".

• Copy ".yt" folder and paste it to "```/internal storage/0/```" (I mean paste it direct in your internal storage, not in any folder.).

• Now, Open Termux (downloaded from Fdroid). 

• Run this command to your Termux.

• Command - [ ```termux-setup-storage``` ]. It will ask for storage permission.

• Command - [ ```pkg update && pkg upgrade``` ] and wait for 3 - 5 minutes.

• Command - [ ```pkg install python && pip install flask && pip install flask_cors``` ]

• Command - [ ```echo alias yt='cd /sdcard/.yt && python app.py' >> ~/.bashrc``` ].

• Then Click Enter. Restart Termux and You're Good to go....

• Now, open Termux again and type [ ```yt``` ]. Wait for 10 second. You'll be redirected to a webpage in chrome. Have Fun. Download your Video.

Everytime you want to download youtube video, Just Open Termux and type [ ```yt``` ] . Wait for 10 second. You'll be redirected to a webpage in chrome.


===================
Made with ♡ By ViruDaya
© ViruDaya | MIT 2025

for legal, check LICENSE.
