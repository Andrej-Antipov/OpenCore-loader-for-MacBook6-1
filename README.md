# OpenCore-loader-for-MacBook6-1
OpenCore configuration for the old MacBook and several other bootloader utilities

![Theme customizable GUI](https://github.com/Andrej-Antipov/OpenCore-loader-for-MacBook6-1/blob/master/Снимок%20экрана%202020-03-27%20в%208.49.47.png)

* BlessLinuxBoot is applet to fast reboot from MacOS in Linux with EFI mode grub bootloader. Searching GRUB in ESP partitions before  execute bless.  Grub must be in ESP partition into EFI/boot folder, as BOOTx64.efi or fbx64.efi. Other grub config files can be into EFI/Ubuntu folder. After has found GRUB will reboot immidiately.
* BlessWINDOWSlegacyBoot is applet to fast reboot in Bootcamp windows with legacy boot. Partition with windows installation must be named as BOOTCAMP to be found. After has found BOOTCAMP will reboot immidiately.
* BlessOpenCoreBoot is applet to reboot for OpenCore bootloader. OpenCore must be installed in any ESP partition to be found by the applet.Reboot manually. 
