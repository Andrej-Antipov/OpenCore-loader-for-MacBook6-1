# OpenCore-loader-for-MacBook6-1
OpenCore configuration for the old MacBook and several other bootloader utilities

1) BlessLinuxBoot is applet to fast reboot from MacOS in Linux with EFI mode grub bootloader. Searching GRUB into ESP before  execute bless.  Grub must be in ESP partition into EFI/boot folder, as BOOTx64.efi or fbx64.efi. Other grub config file can be into EFI/Ubuntu folder. After has found GRUB will reboot immidiately.
2) BlessWINDOWSlegacyBoot is applet to fast reboot in Bootcamp windows with legacy boot. Partition with windows installation must be named as BOOTCAMP to be found. After has found BOOTCAMP will reboot immidiately.
3) BlessOpenCoreBoot is applet to reboot for OpenCore bootloader. OpenCore must be installed in any ESP partition to be found by the applet.Reboot manually. 
