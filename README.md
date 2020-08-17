# platform-asus  

**Volumio platform files for Asus Boards**

Kernel Sources  
http://github.com/TinkerBoard/debian_kernel
(branch "released", currently maintained by Asus, we only support)

Tinkerboard: https://volumio.github.io/docs/, chapter "Porting_Guide"/ "Get_The_Kernel_Source"  

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
2017.11     Asus starts to provide platform files with our help  
2017.11.20  Asus: Upgrade to TinkerOS 2.0.3 uboot and kernel image  
2018.02.06  Asus: rebuild platform-asus based on TinkerOS v2.0.4     
2018.03.26  Asus: rebuild platform-asus based on TinkerOS v2.0.5  
2018.06.02  Volumio: Fixed emergency reboot/ added USB Audio quirks    
2018.07.30  Added support for ES90x8Q2M DAC (overlay)   
2018.07.31  Added signed patch file for kernel 4.4.132+  
2018.08.23  Asus: Confirmed ES90x8Q2M support, Fixed emergency reboot, USB Audio quirks (code base TinkerOSv2.0.8)  
2018.10.23  Asus: Fix for ES90x8Q2M patch  
2018.12.08  Volumio: temporary switch to updated 4.4.71  
2019.01.01 Volumio: Support for more DSD-direct capable USB Audio devices  
2019.01.18 Volumio: changed USB Audio from built-in to module  
2019.05.19 Asus kernel 4.4.132 : trying to address the eq80x8q2m driver frequency issue  
2019.05.21 Revert the above change, stick to 4.4.71+ for the time being for Tinkerboard  
2020.08.17 Backported dwc2 driver from Asus debian_kernel (4.4.132) and applied dwc2 patch (usb audio issue)  



