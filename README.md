

### Installing Ubuntu on VirtualBox (Windows Host)

This lab was completed to get familiar with virtualization and practice installing a Linux-based operating system inside a virtual machine using Oracle VirtualBox. The goal is to build a clean and isolated Ubuntu environment for future cybersecurity, networking, and Linux administration labs.



#### 🧪 Lab Tasks
#### Step 1: Installing Oracle VirtualBox
I started by downloading the latest version of VirtualBox for Windows:

Opened https://www.virtualbox.org/wiki/Downloads

Clicked Windows hosts to download the .exe installer

Ran the installer → clicked Next through the setup wizard

Left all default settings → clicked Install

Clicked Yes when Windows asked for permission

After install, clicked Finish to launch VirtualBox

🔹 Optional: I also installed the VirtualBox Extension Pack for USB 3.0 and other feature support.

#### Step 2: Downloading Ubuntu ISO
I went to https://ubuntu.com/download/desktop

Clicked Download Ubuntu 22.04 LTS

Saved the .iso file (about 4.6 GB) to my Downloads folder

#### Step 3: Creating the Ubuntu Virtual Machine
Inside VirtualBox:

Clicked New

Gave it the name Ubuntu

Selected the ISO file I downloaded

Verified:

Type: Linux

Version: Ubuntu (64-bit)

Allocated 4096 MB of RAM

Created a virtual hard disk:

VDI (VirtualBox Disk Image)

Dynamically allocated

30 GB size

#### Step 4: Installing Ubuntu
Clicked Start on the new VM

Chose Install Ubuntu from the boot screen

Setup process:

Language: English

Keyboard: Default (US)

Installation Type: Normal Installation

Checked “Install third-party software”

Selected Erase disk and install Ubuntu (safe for VM)

Set time zone and user credentials

Installation took ~10 minutes

At the end:

I clicked Restart Now

When asked to remove the installation medium:

Went to Devices > Optical Drives > Remove disk

Then clicked Machine > Reset

Ubuntu booted up successfully into the login screen!

### 🧰 Technology Stack
🪟 Windows 10/11 (host OS)

📦 VirtualBox 7.x.x

🐧 Ubuntu 22.04 LTS ISO

### 🎯 Lab Goal Summary
#### ✅ Installed VirtualBox on Windows

#### ✅ Downloaded Ubuntu Desktop ISO

#### ✅ Created a new Linux VM in VirtualBox

#### ✅ Mounted and booted the Ubuntu ISO

#### ✅ Completed full Ubuntu installation

#### ✅ Successfully launched Ubuntu VM
