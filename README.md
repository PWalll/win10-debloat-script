# win10script
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. I also added Chocolatey and other tools to the script that I install on every machine.

## My Additions

- Dark Mode
- One Command to launch and run
- Chocolatey Install
- O&O Shutup10 CFG and Run
- Added Install Programs
- Added Debloat Microsoft Store Apps

## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
## PWall Modifications
- Optional Install of programs via promts to the user
- Separated Tweaks in diffrent variables for easy editing
- Renamed ForEach to ForEach-Object for less use of aliases
- Seconds in TaskBar Tweak
- Hide the "Look for an app in the Microsoft Store" item in "Open with" dialog
- Remove the "Rich Text Document" item from the "New" context menu
- Hide the "Include in Library" item from the context menu
- Hide the "Print" item from the .bat and .cmd context menu
- Hide the "Edit" item from the images context menu
- Hide the "Create a new video" item from the context menu
- Hide the "Edit with Photos" item from the context menu
- Hide the "Edit with Paint 3D" item from the context menu
- Hide the "Share" item from the context menu
- Hide the "Cast to Device" item from the context menu
- Add the "Run as different user" item to the .exe files types context menu
- Add the "Install" item to the .cab archives context menu