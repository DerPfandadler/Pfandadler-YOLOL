# Material Scanner script by Pfandadler

This YOLOL script allows the user to quickly and easily view the results of a scan performed by a material point scanner.


# Requirements

 - [ ] 1x Material Point Scanner Setup
 - [ ] 1x Basic YOLOL Chip
 - [ ] 1x Text Panel 24x24
 - [ ] 2x Buttons of your choice
### Optional:
For a "cleaner" data network and the ability to have longer and prettier device field names add the following...
 - [ ] 1x Network Relay
 - [ ] 1x Memory Relay
 - [ ] 2x Memory Chips
 
 And as a button label you can use...
 
 - [ ] 1x Progress Bar 12x24

## How to set up the hardware 
Connect your material point scanner and basic YOLOL chip to the Data Network and arrange the Displays however you want.
Example:
![Example](https://cdn.discordapp.com/attachments/718534441428844615/840922334772985856/unknown.png)

## How to set up each device

### Material Point Scanner:

|Default Name|New Name|Default Value|New Value|
|-|-|-|-|                        
|Active|A|0|0|
|Index|I|0|0|
|ScanResults|R|0|0|
|Material|M|""|""|
|Volume|V|0|0|
|Scan|S|0|0|
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
|PanelValue|o|""|""|
|PanelVariableResolution|PanelVariableResolution|1|1|
##

### Button #1:
|Default Name|New Name|Default Value|New Value|
|-|-|-|-|                        
|ButtonState|AS|0|0|
|ButtonOnStateValue|ButtonOnStateValue|1|1|
|ButtonOffStateValue|ButtonOffStateValue|0|0|
|ButtonStyle|ButtonStyle|0|1|

### Button #2:
|Default Name|New Name|Default Value|New Value|
|-|-|-|-|                        
|ButtonState|U|0|0|
|ButtonOnStateValue|ButtonOnStateValue|1|1|
|ButtonOffStateValue|ButtonOffStateValue|0|0|
|ButtonStyle|ButtonStyle|0|1|
>When using buttons that don't have all the device fields listed above ignore the missing ones.
> **ProTip:** You can use **Progress Bars** as labels for small buttons...


## Advanced Setup

SOON:tm: