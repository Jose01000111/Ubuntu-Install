### ⬇️Installing Ubuntu on VirtualBox (Windows Host)

<p align="center">
<img src="https://i.imgur.com/2OFLrPP.png" alt="osTicket logo"/>
</p>

***

This lab was completed to get familiar with virtualization and practice installing a Linux-based operating system inside a virtual machine using Oracle VirtualBox. The goal is to build a clean and isolated Ubuntu environment for future cybersecurity, networking, and Linux administration labs.

#### 🧪 Lab Tasks
#### Step 1: Installing Oracle VirtualBox
I started by downloading the latest version of VirtualBox for Windows:

<p align="center">
<img src="https://i.imgur.com/QwT7GoJ.png" alt="osTicket logo"/>
</p>

***

[VirtualBox Download](https://www.virtualbox.org/wiki/Downloads)

<p align="center">
<img src="https://i.imgur.com/VKYai3Z.png" alt="osTicket logo"/>
</p>

***

I clicked on the Windows hosts link to download the .exe installer. Once the download finished, I ran the installer and clicked Next through the setup wizard. I left all the default settings as they were and clicked Install. When Windows asked for permission, I clicked Yes to proceed. After the installation completed, I clicked Finish to launch VirtualBox

#### Step 2: Downloading Ubuntu ISO

I went to https://ubuntu.com/download/desktop, clicked Download Ubuntu 22.04 LTS, and saved the .iso file—about 4.6 GB—to my Downloads folder.

<p align="center">
<img src="https://i.imgur.com/zolFBCp.png" alt="osTicket logo"/>
</p>

***

#### Step 3: Creating the Ubuntu Virtual Machine
Inside VirtualBox, I clicked New to create a new virtual machine. I named it Ubuntu and selected the ISO file I had downloaded earlier. I verified the settings to make sure the Type was set to Linux and the Version was Ubuntu (64-bit). I allocated 4096 MB of RAM to the VM. For storage, I created a virtual hard disk using the VDI (VirtualBox Disk Image) format, set it to be dynamically allocated, and gave it a maximum size of 30 GB.

<p align="center">
<img src="https://i.imgur.com/cUrcCSb.png" alt="osTicket logo"/>
</p>

***

<p align="center">
<img src="https://i.imgur.com/FMAfi60.png" alt="osTicket logo"/>
</p>

***

<p align="center">
<img src="https://i.imgur.com/3PEdBtl.png" alt="osTicket logo"/>
</p>

***

#### Step 4: Installing Ubuntu
I clicked Start on the new VM and, from the boot screen, chose Install Ubuntu. During the setup process, I selected English as the language and kept the default US keyboard layout. I chose the Normal Installation option and checked the box to Install third-party software. For the installation type, I selected Erase disk and install Ubuntu, which is safe since it's running in a virtual machine. I then set my time zone and created my user credentials. The installation took about 10 minutes. At the end, I clicked Restart Now. When prompted to remove the installation medium, I went to Devices > Optical Drives > Remove disk, then clicked Machine > Reset. After that, Ubuntu booted up successfully and brought me to the login screen!

<p align="center">
<img src="https://i.imgur.com/wxfEgIC.png" alt="osTicket logo"/>
</p>

***

Ubuntu booted up successfully into the login screen!

### 🧰 Technology Stack
🪟 Windows 11 (host OS)

📦 VirtualBox

🐧 Ubuntu 22.04 LTS ISO

### 🎯 Lab Goal Summary
#### ✅ Installed VirtualBox on Windows

#### ✅ Downloaded Ubuntu Desktop ISO

#### ✅ Created a new Linux VM in VirtualBox

#### ✅ Mounted and booted the Ubuntu ISO

#### ✅ Completed full Ubuntu installation

#### ✅ Successfully launched Ubuntu VM
