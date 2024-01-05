## EZ-FLASH OMEGA Kernel

Decided to modify the Omega Kernel to allow quick booting of games stored in NOR without having to go through the menus.\
In order to enable it, go to the options menu, press right or left to switch pages, and toggle the option on.\
Once enabled, if you want to go back to the Omega menu, hold L on boot-up.\
This also works to launch the most recently played game, regardless of if it was stored in NOR or not, just hold A on boot-up.


## How to build 

    1.We use devkitARM_r47, you can use the current version or newer.
    2.Set the following environment variables in system, or modify the value in build.bat, based on your installation path
 
        PATH,DEVKITARM,DEVKITPRO,LIBGBA

    3.Double click on build.bat under winodws. If it goes well, you will get ezkernel.gba
    4.Rename the ezkernel.gba to ezkernel.bin, that is the omega kernel upgrade file

#### KNOWN ISSUE:

Somehow I messed up the Chinese characters when you switch languages. I'm not sure what might be causing this, but I suspect it might be some sort of buffer overflow from adding the new english options. Feel free to let me know what it might be!
