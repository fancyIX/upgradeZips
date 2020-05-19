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

# After Unzip
## To Allow "Clover Configurator" Run
Quit out of System Preferences

Open the Terminal app from the /Applications/Utilities/ folder and then enter the following command syntax:

sudo spctl --master-disable

Hit return and authenticate with an admin password

Relaunch System Preferences and go to “Security & Privacy” and the “General” tab

You will now see the “Anywhere” option under ‘Allow apps downloaded from:’ Gatekeeper options
