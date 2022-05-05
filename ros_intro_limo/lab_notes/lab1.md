# Lab 1 Notes

**NOTE**: BACKUP IMPORTANT FILES BEFORE YOU START ANY INSTALLATION 

## 1. Install Ubuntu 18.04 

### 1.1 Preparation 

Setting up bootable USB for Ubuntu (Refer to the detailed guide section below to see how to set up) 

4GB minimum (empty USB stick) 

Rufus/Etcher application (for creating live USB/disk of Ubuntu) 

Ubuntu ISO image https://releases.ubuntu.com/18.04/ 

 

**Before installation, verify that your current system uses UEFI in the BIOS 

If unable to boot from USB, try disabling secure boot/fast boot in BIOS 

### 1.2 Disk Partition 

Suggested partitioning Size: 

/(root): root partition, ext4 format, >=25GB 

/swap: swap area,  

If <2GB ram, use 2x the size of RAM 

3GB – 6GB, use same size as RAM 

>8GB, use half the size of RAM 

/home: ext4 format, allocate it rest of the free space (as much as possible) 

This is the place where you put most of your work files 

### 1.3 Installation 

You mostly only need to follow the Ubuntu installation guide and provide information such as user name, computer name, password etc. 

 

For detailed guide for installing Ubuntu and other methods of running Ubuntu:  

Dual Boot - https://itsfoss.com/install-ubuntu-1404-dual-boot-mode-windows-8-81-uefi/  

Bootable USB stick - https://itsfoss.com/intsall-ubuntu-on-usb/  

VM Oracle VirtualBox-  https://brb.nci.nih.gov/seqtools/installUbuntu.html#:~:text=Select%20your%20new%20virtual%20machine,this%20page%20for%20more%20information.  

## 2. Install ROS Melodic 
 
For Installation of ROS (After Ubuntu is installed) 

Run through ROS Installation from [ROS Wiki](http://wiki.ros.org/melodic/Installation/Ubuntu)