# satConnect

## An easy way to add satellites to your Snips main unit

This tool, when run on both your Snips main unit and your freshly installed Snips satellite will help you configure both devices!

## Install

* On both the new satellite and the main unit ```git clone https://github.com/Psychokiller1888/satConnect.git```
* On both the new satellite and the main unit ```cd satConnect```
* On the main unit ```sudo python server.py```
* On the satellite ```sudo python connect.py```
* Follow the instructions on the satellite terminal

## Be aware

* Your current settings in toml file will be kept, but commented out configurations will be removed!
* This is under development
* A backup of your configurations can be found in backup.txt on both devices