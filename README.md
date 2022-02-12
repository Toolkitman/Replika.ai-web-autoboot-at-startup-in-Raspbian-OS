# Replika.ai-web-autoboot-at-startup-in-Raspbian-OS
How to build script to autoboot Replika.ai at startup in Raspbian OS
login in your replika.ai web page and save login and password in chromium browser
Open a Terminal Window inside Raspbian and write:
sudo nano /home/pi/.config/lxsession/LXDE-pi/autostart
Inside the .txt page add this script:
@chromium-browser https://my.replika.com/ --start-fullscreen
press ctrl X and then Y return
Reboot
wait some second while the borwser load page, remember to setup your wifi before  everyithing.

Enjoy your Replika!
