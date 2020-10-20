# archinstall
Simple Bash script to install Arch Linux on UEFI systems
Very WIP, some things may not work properly, plus I'm not great at bash

# Instructions:
0. This script is only compatible with UEFI systems
1. Put the scripts in the root account's home folder (/root) on your live environment
2. Partition and mount your disks to /mnt, make sure you mount your EFI partition as well
3. Run stage1_archinstall.sh to install the base system
4. stage1 will automatically put you in chroot of the new system, simply run ./stage2_archinstall.sh to finish the installation
