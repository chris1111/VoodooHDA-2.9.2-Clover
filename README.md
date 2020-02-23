


# VoodooHDA 2.9.2-V14 


## (Support macOS Catalina 10.15)
- Latest Update 23 Fev 2020 Adapted for macOS Catalina 10.15.4 Remove VoodooHdaSettingsLoader.app which is not necessary.
- Update 13 July 2019 Add missing AppleHDADisabler.kext for 10.15 Clasic mode.
- New background support dark mode.

### This is a Mac OS X Package

### Credit:
- Developer Slice, Zenith432, autumnrain ➠ Source: https://sourceforge.net/projects/voodoohda/
- MountEFI Script 10.13/10.14 Clover Team
- Testeurs: emax31, arcade33, MilesTEG1, PhilouFr, emilio36, fredsame, aminov41, sevan, JMB.
- Packager chris1111


VoodooHDA is an open source audio driver for devices compliant with the Intel High Definition Audio (HDA) specification.
It is intended as an Intel-only replacement for AppleHDA on Mac OS X with support for a wide range of audio controllers and codecs. Working for 10.14/10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6!  


### Instructions: 
- You need Existing Clover V2.4k. This does not install Clover, it will install only VoodooHDA and the other required components to its proper function.

### Method-1 for Clover UEFI /ESP
- This program can install VoodooHDA kernel extension on ESP (EFI System Partition) /EFI/CLOVER/kexts/10.14/10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6
- It's up to you to choose witch one. The kext will be inject by Clover

### Method-2 for Clover Legacy
- This program can install VoodooHDA kernel extension on /EFI/CLOVER/kexts/10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6
- It's up to you to choose witch one. The kext will be inject by Clover


### Method-3 Clasic Method 
- You can also select Clasic method for 10.6 to 10.14
- This will install the VoodooHDA.kext + AppleHDADisabler.kext on /System /Library /Extensions
- This will install also VoodooHdaSettingsLoader.app on Applications and VoodooHDA.prefPane on Library / PreferencePanes  

### getdump
- getdump is installed on usr/local/bin/getdump for all the methods mentioned

### VoodooHDA.prefPane
- For all OS X System VoodooHDA.prefPane is installed on Library/PreferancesPanes

### Usage: Download the Latest Release ➣ [VoodooHDA 2.9.2 Clover-V15](https://github.com/chris1111/VoodooHDA-2.9.2-Clover-V13/releases/tag/V-15) Choose the option you want, install and reboot. 

### Verry important to Reboot for the changes to be applied.

### Common issue [Common issue ➤ VoodooHDA ](http://www.insanelymac.com/forum/topic/267905-voodoohda-common-problems/)

### Any issue post here [Main topic ➤ VoodooHDA ](http://www.insanelymac.com/forum/topic/314406-voodoohda-290/)

### Follow every steps in the Video
                       ⟱

[![Modular Image Creation](https://i95.servimg.com/u/f95/18/50/18/69/video_10.png)](https://youtu.be/RYHI2LGBqMc)
