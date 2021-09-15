# Material Scanner script by Pfandadler
This YOLOL script allows any user to quickly and easily view the results of a scan performed by a material point scanner.

# pre-V3 Out NOW!
This is the pre-release version of version 3 of my material point scanner script. It adds new features, makes using it even easier but will probably still break in some edge cases. If you find any issues please create an issue either here on Github or message me on Discord at DerPfandadler#0001.
### NewFeatures!

 - Fully automatic **asteroid classification**
 - Volume **output now in stacks** instead of useless kilovoxels
 - More **energy efficient**
 - New formatting
 - Shorter delay between scans
 - Fancy errors screens for when a scan fails
 - The manual update button has been removed as autoscan now works much better
 - **And a bunch of smaller additions and fixes!**

# Requirements

 - [ ] 1x Material Point Scanner Setup
 - [ ] 1x Basic YOLOL Chip
 - [ ] 1x Text Panel 24x24
 - [ ] 1x Button of your choice
 
 And as a button label you can use...
 
 - [ ] 1x Progress Bar 12x24
 
## Which edition of the script should I use?
Both versions are functionally identical. They just differ in what characters they use.
### The "SSC Edition": 
It can only be properly pasted into a Yolol chip trough the Yolol editor in the SSC. So only use it when you want to either design a ship in the SSC with this script or buy the Yolol chip with the script pasted onto it from the SSC.

### The "In-universe Edition":
It can be pasted anywhere **but** to enable that I had to replace the fancy characters I use for the formatting with boring ones. This version of the script is less tested and I only recommend using it if you have no way of getting a Yolol chip with the script pasted onto it from the SSC.

## How to set up the hardware
Connect your material point scanner and basic YOLOL chip to the Data Network and arrange the displays and buttons however you want.
I recommend a setup like this for your text panel, button and optional progress bar:
![Example](https://cdn.discordapp.com/attachments/718534441428844615/876405989425963048/unknown.png)


## How to set up all device fields

### Material Point Scanner:

|Default Name|New Name|Default Value|New Value|
|-|-|-|-|                        
|Active|AC|0|0|
|Index|IN|0|0|
|ScanResults|SR|0|0|
|Material|MA|""|""|
|Volume|VO|0|0|
|Scan|SC|0|0|
|Reset|Re|0|0|
##

### Basic YOLOL Chip:
|Default Name|New Name|Default Value|New Value|
|-|-|-|-|                        
|Chipwait|Chipwait|0|0|
##

### Text Panel 24x24:
|Default Name|New Name|Default Value|New Value|
|-|-|-|-|                        
|PanelValue|AutoScan|""|""|
|PanelVariableResolution|PanelVariableResolution|1|1|
##

### Button:
|Default Name|New Name|Default Value|New Value|
|-|-|-|-|                        
|ButtonState|AS|0|0|
|ButtonOnStateValue|ButtonOnStateValue|1|1|
|ButtonOffStateValue|ButtonOffStateValue|0|0|
|ButtonStyle|ButtonStyle|0|1|
>When using a button that doesn't have all the device fields listed above ignore the missing ones.
> **ProTip:** You can use **Progress Bars** as labels for small buttons...


## Advanced Setup

When FB get their shit with new device fields together.....