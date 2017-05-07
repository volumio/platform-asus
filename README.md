# platform-asus  

**Volumio platform files for Asus Boards**

Kernel Sources  
http://github.com/TinkerBoard/debian_kernel


**Still Work-In-Proress, more info to be supplied....**  

Tinkerboard: see http://192.168.0.250:8080/Porting_Guide/Get_The_Kernel_Source  

This repo contains all files, used by the Volumio Builder to create a **Asus Tinkerboard** image  

- kernel files (kernel, modules, firmware)  
- u-boot  
- other files. e.g. kernel configuration etc.  

**Changelog**

2017.05.02  Beta version  
2017.05.04  Moved from Armbian build to the Asus Tinkerboard repo  
  	    Beta version with boot/ reboot/ wlan/ hotspot/ fixed mac addr/ USB Audio/ cifs/ nfs  
2017.05.05  Added heartbeat led, backed up 2 important patches in folder /patches  
2017.05.06  Changed to booting from vfat partition and using extlinux/extlinux.conf instead of boot.scr  
2017.05.07  Changed pretty name of Realtek ALC4040 usb audio card from "Audio" to "TinkerAudio"  



