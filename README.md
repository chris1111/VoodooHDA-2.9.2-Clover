# VoodooHDA 2.9.0-V11 
## (Support macOS High Sierra)

### This is a Mac OS X Package

### Credit:
- Developer Slice, Zenith432, autumnrain ➠ Source: https://sourceforge.net/projects/voodoohda/
- MountEFI Script 10.13 Clover Team
- Testeurs: emax31, arcade33, MilesTEG1, PhilouFr, emilio36, fredsame, aminov41, sevan, JMB.
- Packager chris1111


VoodooHDA is an open source audio driver for devices compliant with the Intel High Definition Audio (HDA) specification.
It is intended as an Intel-only replacement for AppleHDA on Mac OS X with support for a wide range of audio controllers and codecs.
 
Working for 10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6!  


### Instructions: You need Existing Clover V2.4k. This does not install Clover, it will install only VoodooHDA and the other required components to its proper function.

### Method-1 for Clover UEFI /ESP
- This program can install VoodooHDA kernel extension on ESP Partition /EFI/CLOVER/kexts/10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6
### It's up to you to choose witch one. The kext will be inject by Clover

### Method-2 for Clover Legacy
- This program can install VoodooHDA kernel extension on /EFI/CLOVER/kexts/10.13/10.12/10.11/10.10/10.9/10.8/10.7/10.6
### It's up to you to choose witch one. The kext will be inject by Clover


### Method-3 Clasic Method
- You can also select Clasic method for 10.6 to 10.13
- This will install the VoodooHDA.kext + AppleHDADisabler.kext on /System /Library /Extensions
- This will install also VoodooHdaSettingsLoader.app on Applications and VoodooHDA.prefPane on Library / PreferencePanes  

### getdump is installed on usr/local/bin/getdump for all the methods mentioned

### Common issue [Common issue ➤ VoodooHDA ](http://www.insanelymac.com/forum/topic/267905-voodoohda-common-problems/)

### Any issue post here [Main topic ➤ VoodooHDA ](http://www.insanelymac.com/forum/topic/314406-voodoohda-290/)

### Note:
For all OS X System VoodooHDA.prefPane is installed on Library/PreferancesPanes
### Usage: Download the Latest Release [Download ➤ VoodooHDA 2.9.0-V11 ](https://github.com/chris1111/VoodooHDA-2.9.0-Clover-V11/releases) Choose the option you want, install and reboot. 
### Verry important to Reboot for the changes to be applied.

### Follow every steps in the Video

[![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/68747411.jpg)](https://www.hackintosh-montreal.com/h30-voodoohda-repos)
