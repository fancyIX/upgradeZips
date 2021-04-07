# Before Using Zip Files
## Disapble SIP

Click the Apple symbol in the Menu bar.

Click Restart…

Hold down Command-R to reboot into Recovery Mode.

Click Utilities.

Select Terminal.

Type csrutil disable.

Press Return or Enter on your keyboard.

Click the Apple symbol in the Menu bar.

Click Restart…

* Details in: https://www.macworld.co.uk/how-to/mac/how-turn-off-mac-os-x-system-integrity-protection-rootless-3638975/

# After Unzip
## To Allow "Clover Configurator" Run
Quit out of System Preferences

Open the Terminal app from the /Applications/Utilities/ folder and then enter the following command syntax:

sudo spctl --master-disable

Hit return and authenticate with an admin password

Relaunch System Preferences and go to “Security & Privacy” and the “General” tab

You will now see the “Anywhere” option under ‘Allow apps downloaded from:’ Gatekeeper options

* Details in: https://osxdaily.com/2016/09/27/allow-apps-from-anywhere-macos-gatekeeper/

# To Install

https://www.youtube.com/watch?v=7wWfU3AlFPk
