### Process status

- [``Installable``](https://github.com/17x/hackintosh-i5-10400-asrock-b460m-steel-legend/releases/tag/installable)

  Use this EFI you can successfully finish installation and enter system UI interface, all things are fine but ethernet are ``not working`` , a part of usb ports ``cannot be use``, and ``never been wake up`` from sleep status by interaction from mouse or keyboard.
  
- [``Usable``](https://github.com/17x/hackintosh-i5-10400-asrock-b460m-steel-legend/releases/tag/usable)

  Use this EFI you can use ethernet by certain configs, all USB ports work properly.
  
  <img src="./assets/eth-0.png" width="500" height="433">
  
  <img src="./assets/eth-1.png" width="500" height="433">
  
  [``Wake-able``](https://github.com/17x/hackintosh-i5-10400-asrock-b460m-steel-legend/releases/tag/wake-able)
  
  Custom the SSDT-EC.aml file to `speed up boot`, remove all unnecessary boot-args, set layout-id id (ALC1200) in config.plist, `boot-args` field value to `igfxonln=1` so your Monterey can wake up with monitor display. A weird issue is Ethernet cannot be change to 1000M or 2500M that's really disappoint me cause realtek8125 kext never been update since April 30 in this year.



### Systems

[Open Core 0.7.5](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.7.5)

[Monterey 12.0.1](https://cloud.mfpud.com/Hackintosh/241BB3B9B9FF8D2CDDEDD9972CC34099/macOS%20Monterey%2012.0.1%20Clover%20and%20OC%20with%20PE.dmg)



### Hardware list

Intel I5-10400

AsRock b460M steel legend

ADATA 16GB * 2

WD SN750 500GB



<img src="./assets/inside-case.jpg" width="500" height="666">

<img src="./assets/system-ui.png" width="500" height="295">

