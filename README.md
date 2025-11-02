# youtube-downloader
This is a YouTube Downloader Tool for Termux in Android Only.

==================================

Note: Use Zarchiever App for better experience. Make sure to enable "Show hidden Files"

**Some common things**

If the terminal writes "Do you want to continue? [Y/n]" , then simply write "y" (small lettered) and press enter.
Your downloaded videos or audios will be saved in Your Download folder in Internal Storage.

--------------------------

• Extract "yt.zip". You'll get a folder ".yt".
• Copy this folder and paste it to "/internal storage/0/" (are mera matalab hai direct internal storage me. Naaki kisi folder me).
• Now, install "termux.apk" and open it. 
• Run this command to your Termux.
• Command - [ termux-setup-storage ]. It will for storage permission.
• Command - [ pkg update && pkg upgrade ] and wait for 3 - 5 minutes.
• Command - [ pkg install python && pip install flask && pip install flask_cors]
• Command - [ nano ~/.bashrc ].
• Paste there [ alias yt='cd /sdcard/.yt && python app.py' ]
• Then click on **CTRL** + X 
• Then type Y. 
• Then Click Enter. Close Termux and You're Good to go....
• Open Termux Again and type [ yt ]. Wait for 10 second. You'll be redirected to a webpage in chrome. Have Fun. Download your Video.

Everytime you want to download youtube video, Just Open Termux and type [ yt ] . Wait for 10 second. You'll be redirected to a webpage in chrome.


===================
Made with ♡ By ViruDaya
© ViruDaya | MIT 2025

for legal, check LICENSE.
