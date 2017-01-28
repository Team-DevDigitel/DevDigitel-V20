# DevDigitel-V20



PREQUISITS:

This is a DECRYPTED rom and requires that you are boot-loader unlocked and have access to twrp.
If you have not wiped your system and formatted data do so now, unless you want a brick... 
After flashing the rom i suggest wiping cache and dalvik cache again then rebooting.
YOU NEED TO WIPE ALL DATA AND FORMAT DATA TO USE MY ROM

Ok and the disclaimer part : I can't be held responsible for the effects of this software, it was designed for testing purposes and fun only on my free time. Please make a backup, make sure you have a computer handy with adb and fastboot and take sometime to read all documents before proceeding, you've been warned. 




Installation Steps:

1.) Download desired Rom Version from below download link(s)

2.) Place Rom preferably on external SD card

3.) Reboot device into recovery either using Busybox, shell command, or from device powered off method. (instructions in post#3)

4.) Once in recovery its HIGHLY recommended to install on a clean device. Select Wipe, Then advanced,
put check marks next to System, Dalvik-Cache, Data, Cache

5.) Once wipe is completed, back up one step and choose FORMAT DATA, it will require you to type YES to complete.

6.) When completed return back to Main TWRP screen, Click Mount and make sure System and Data are mounted.

7.) Choose Install then Navigate to where you placed Rom ( You made need to choose SD as the storage location if you put on SD )

9.) Install Rom and wait for it to complete. Once done, select reboot and WAIT.


The install process will take some time, later builds have zip-align at boot to help with de-odexed speeds, the boot logos have also been turned of on some newer builds so don't freak out, just wait until you hear the Voice assistant start her speach.
At this point the screen will be out of wack, many moving colors and such, this is normal due to using sprints boot.img with the debug boot-loader that gave us the unlocked / root ability. Once you hear the Voice assistant start up, cover the proximity sensor near the front camera and lock the screen. Once both the top and main screen go black, just unlock the screen and continue with setup. The static image will re-occur on any full re-boot. To avoid this check out the Modified Kernels post for Alt. Kernels that resolve this. Be aware I do NOT support these other images, and i'm unable to help with issues you have if you choose that route. Please post in the Kernels page where you got the Kernel for best support!


KERNEL / BOOT IMG INFO-FAQ
The Kernels I include are all STOCK and matching the version of software they were built for. I do not build from source so source code would be the orignial LG source. All ive done is disabled the dm-checks, boot loader checks, force encrypt off. There is no OC/OV/UC/UV in these kernels, please see below link for alternative options that can be used, but aren't officially supported by me and may not work fully with my roms.
