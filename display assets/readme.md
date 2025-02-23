If you have the stock icons and display assets you don't need to update the display to use this firmware. Currently Creality provides several types of screen units:

**DWIN display**, originally found in Ender 3V2  
[![Ender3v2-DWIN](https://user-images.githubusercontent.com/2745567/156829365-a58a3afc-77e3-40b9-9e16-5edfe3073de8.jpg)](https://raw.githubusercontent.com/mriscoc/Ender3V2S1/Ender3V2S1-Released/display%20assets/displays/DWIN.jpg)

**DACAI display**, found in Ender 3S1 and in some new Ender 3V2) [Updated firmware for enable G-code preview](https://github.com/mriscoc/Ender3V2S1/blob/Ender3V2S1-Released/display%20assets/dacai_update.zip?raw=true)  
[![Ender3S1-DACAI](https://user-images.githubusercontent.com/2745567/156829472-2c38a4ab-bdde-4c21-b78f-a30692c96500.jpg)](https://raw.githubusercontent.com/mriscoc/Ender3V2S1/Ender3V2S1-Released/display%20assets/displays/DACAI.jpg)
  
**SYNWIT (VIEWE)** display, currently update is not supported, some users [report problems](https://github.com/mriscoc/Ender3V2S1/issues/323) with this screen.   
[![VIEWE](https://user-images.githubusercontent.com/2745567/163235004-1d3f1ed4-e149-4ca8-ae60-438df5f0b70a.png)](https://raw.githubusercontent.com/mriscoc/Ender3V2S1/Ender3V2S1-Released/display%20assets/displays/SYNWIT1.jpg)
[![SYNWIT2R](https://user-images.githubusercontent.com/2745567/209407402-25053f01-6a5d-4c76-90c8-da5aec43100c.png)](https://raw.githubusercontent.com/mriscoc/Ender3V2S1/Ender3V2S1-Released/display%20assets/displays/SYNWIT2.jpg)

**TJC** display, currently this display needs a custom compile: [TJC issues](https://github.com/mriscoc/Ender3V2S1/issues/542).  
[![TJC](https://user-images.githubusercontent.com/2745567/206931166-24185525-e377-472e-9bed-37a39aab24fb.jpg)](https://raw.githubusercontent.com/mriscoc/Ender3V2S1/Ender3V2S1-Released/display%20assets/displays/TJC.jpg)

The `DWIN_SET` display firmware / icon assets only apply to the DWIN display, for the DACAI screens, you should use the `private` display firmware / icon assets.

# Display firmware, boot image and icons compilations
This page list the display assets compilations compatible with [Professional firmware](https://github.com/mriscoc/Ender3V2S1/releases/latest).

## How to install
1. Get an µSD card of 8GB or less.
1. Format the µSD card MBR, FAT32 and with a 4 KB sector size
1. Copy the `DWIN_SET`(DWIN) or `private`(DACAI) folder in the Root of SD
1. Turn off your printer
1. Disconnect and disassembly the screen unit
1. Install the µSD card into the slot of the screen unit
1. Reconnect the screen to the printer
1. Turn on the printer and wait for the display to change color from blue to
  orange
1. Verify that the screen assets were updated
1. Turn off the printer and remove the µSD card from the screen unit
1. Reassembly the screen unit  
  
If you want to change only the icons of the DWIN screen, then you can leave only the **9.ICO** file
inside of the DWIN_SET folder.  
If you weren't able to update the display, verify the format of the µSD Card
(MBR, FAT32 and allocation unit of 4096 bytes) and the CRC of the files.
  
<img src="https://raw.githubusercontent.com/mriscoc/Ender3V2S1/Ender3V2S1-Released/display%20assets/DWIN_SET-folder.jpg" height="350" />  

Be sure to leave **only** the `DWIN_SET` or `private` folder at the root of the card.  
  
<br>
  
---

## [Go to Stock display firmware](https://github.com/mriscoc/Ender3V2S1/tree/Ender3V2S1-Released/display%20assets/stock)  

<a href=https://github.com/mriscoc/Ender3V2S1/tree/Ender3V2S1-Released/display%20assets/stock><img src="https://raw.githubusercontent.com/mriscoc/Ender3V2S1/Ender3V2S1-Released/display%20assets/stock/preview1.jpg" height="400" /></a>  
  
<br>
  
---

## [Go to Giadej compilation](https://github.com/mriscoc/Ender3V2S1/tree/Ender3V2S1-Released/display%20assets/Giadej%20compilation)

<a href=https://github.com/mriscoc/Ender3V2S1/tree/Ender3V2S1-Released/display%20assets/Giadej%20compilation><img src="https://raw.githubusercontent.com/mriscoc/Ender3V2S1/Ender3V2S1-Released/display%20assets/Giadej%20compilation/preview1.jpg"  height="400" /></a>  
  
<br>
  
---

### Updating printer firmware
For update your printer firmware and get the latest version go here: <https://github.com/mriscoc/Ender3V2S1/releases/latest>  


