# hacker tools

**a list of tools that can be used for it repair and maintenance.**

this is not an exhaustive list, only intended to be a starting point for those looking to build a toolkit.

while these may be useful to a networking and server admins, the tools are chosen for their ability to quickly diagnose and repair common issues on a personal computer (failing harddrives, backups, settings, scanning for malware, etc).

keep these on a usb drive for easy access, and look for portable versions.

## contents

- [contributing](#contributing)
- [macos](#macos)
  - [files and data](#files-and-data)
  - [malware removal and security](#malware-removal-and-security)
  - [data recovery and backup](#data-recovery-and-backup)
  - [specs, monitoring and hardware health](#specs-monitoring-and-hardware-health)
  - [networking and connectivity](#networking-and-connectivity)
  - [other tools](#other-tools)
  - [mac terminal commands](#mac-terminal-commands)
- [windows](#windows)
  - [files and data](#files-and-data-1)
  - [malware removal and security](#malware-removal-and-security-1)
  - [data recovery and backup](#data-recovery-and-backup-1)
  - [usb and bootable drives](#usb-and-bootable-drives)
  - [specs, monitoring and hardware health](#specs-monitoring-and-hardware-health-1)
  - [networking and connectivity](#networking-and-connectivity-1)
  - [windows terminal commands](#windows-terminal-commands)
- [linux](#linux)
  - [files and data](#files-and-data-2)
  - [malware removal and security](#malware-removal-and-security-2)
  - [data recovery and backup](#data-recovery-and-backup-2)
  - [specs, monitoring and hardware health](#specs-monitoring-and-hardware-health-2)
  - [networking and connectivity](#networking-and-connectivity-2)
  - [linux terminal commands](#linux-terminal-commands)

## contributing

please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for more information on how to contribute.

## macos

### files and data

- **[Homebrew](https://brew.sh/)** is a package manager. it allows you to install, manage and update software packages from the command line instead of using the app store or downloading and installing them manually.

- **[Keka](https://www.keka.io/)** is a versatile file archiver. it is a simple and efficient tool to compress and extract files. similar to winrar or 7-zip.

- **[DaisyDisk](https://daisydiskapp.com/)** is a disk space analyzer for macos. it shows you what's taking up space on your hard drive and allows you to free up space by deleting unneeded files.

- **[AppCleaner](https://freemacsoft.net/appcleaner/)** is a small application that allows you to thoroughly uninstall unwanted apps. it also allows you to manage startup items and widgets.

- **[CleanMyMac X](https://macpaw.com/cleanmymac)** is a utility for cleaning, optimizing, and maintaining your mac. it scans your entire system, removes gigabytes of junk in just two clicks, and monitors the health of your mac.

### malware removal and security

todo.

### data recovery and backup

- **fsck** is a built-in command-line utility that can be used to check and repair filesystems, often able to recover data from bad sectors even when other tools fail. sometimes useful on other operating systems as well, if booted from a live cd.

- **[DFU Blaster](https://bitbucket.org/twocanoes/dfu-blaster-public/downloads/)** is a tool that blasts the device firmware update mode to your macos device, allowing you to restore the device to factory settings. it is useful because triggering it can be difficult on some devices. [read more](https://support.apple.com/en-gb/108900)

### specs, monitoring and hardware health

todo.

### networking and connectivity

- **[nmap](https://nmap.org/)** is a free and open-source network scanner. nmap is used to discover hosts, ports and services on a computer network by sending packets and analyzing the responses.

### other tools

- **[iTerm2](https://iterm2.com/)** is a replacement for terminal and the successor to iterm. iterm2 brings the terminal into the modern age with features like drop-down windows, split panes, and AI that can autocomplete your commands.

- **[Apple Configurator](https://support.apple.com/apple-configurator)** is a free macos application that allows you to configure and deploy devices. it can be used to install profiles, update software, and supervise devices on a device or many devices at once.

- **[Keyboard Clean Tool](https://folivora.ai/keyboardcleantool)** is a simple application that disables your keyboard and trackpad while cleaning them.

- **Activity Monitor** is a built-in macos utility that provides information about how your mac is using its resources. it shows the processes that are running, how much cpu they are using, how much memory they are using, and how much network bandwidth they are using.

### mac terminal commands

```bash
# run commands in terminal

# keep screen on & prevent sleep
caffeinate -d

# check network speed
networkquality

# check network info
ifconfig

# check wifi info
networksetup -getinfo wi-fi

# check for macos updates & install
softwareupdate -i -a

# restart iCloud services
killall bird
```

## windows

### files and data

- **[CCleaner](https://www.ccleaner.com/)** is a freeware system optimization, privacy and cleaning tool. it removes unused files from your system allowing windows to run faster and freeing up valuable hard disk space.

- **[BleachBit](https://www.bleachbit.org/)** is a free and open-source disk space cleaner, privacy manager, and computer system optimizer. it can free up disk space, maintain privacy, and remove junk. similar to ccleaner.

- **[7-Zip](https://www.7-zip.org/)** is a file archiver with a high compression ratio. it is free software with open source.

- **[qBittorrent](https://www.qbittorrent.org/)** is a free, open-source, and cross-platform bittorrent client. it aims to provide an open-source software alternative to µtorrent.

- **[Checksum Control](https://checksumcontrol.sourceforge.io/)** is a program to verify and write checksumfiles. it supports sfv and md5, even some exotic md5 file types. very easy to use, with a wizard interface.

- **[Revo Uninstaller](https://www.revouninstaller.com/)** is a freeware uninstall utility. it has powerful features to uninstall programs scanning for leftover files, folders, and registry entries after uninstall.

- **[WinDirStat](https://windirstat.net/)** is a disk usage statistics viewer and cleanup tool for various versions of microsoft windows.

### malware removal and security

- **[Emsisoft Emergency Kit](https://www.emsisoft.com/en/home/emergencykit/)** is a collection of programs that can be used without software installation to scan for malware and clean infected computers.

- **[KillEmAll](https://www.d7xtech.com/killemall/)** is a portable utility to close all non-essential programs and restart processes. it is designed to be used in emergency situations to restart processes that have been terminated by malware.

### data recovery and backup

- **[Recuva](https://www.ccleaner.com/recuva)** can recover files that have been accidentally deleted from your computer. this includes files emptied from the recycle bin as well as images and other files that have been deleted by user error from digital camera memory cards or mp3 players.

### usb and bootable drives

- **[Rufus](https://rufus.ie/)** is a utility that helps format and create bootable USB flash drives, such as USB keys/pendrives, memory sticks, etc.

- **[UNetbootin](https://unetbootin.github.io/)** allows you to create bootable live usb drives for ubuntu and other linux distributions without burning a CD.

- **[WinCDEmu](https://wincdemu.sysprogs.org/)** is an open-source cd/dvd/bd emulator - a tool that allows you to mount optical disc images by simply clicking on them in windows explorer.

### specs, monitoring and hardware health

- **[Speccy](https://www.ccleaner.com/speccy)** is an advanced system information tool for your PC. need to find out what's inside your computer? speccy will give you all the information you need.

- **[HWiNFO](https://www.hwinfo.com/)** is a professional hardware information and diagnostic tool supporting the latest components, industry technologies, and standards.

- **[CPU-Z](https://www.cpuid.com/softwares/cpu-z.html)** is a freeware system profiling and monitoring application that detects the CPU, ram, motherboard chipset, and other hardware features.

- **[GPU-Z](https://www.techpowerup.com/gpuz/)** is a lightweight utility designed to give you all information about your video card and GPU.

- **[SSD-Z](https://aezay.dk/aezay/ssdz/)** is a free software that gathers information on some of the main components of your system, including your SSD or hard drive, so you can monitor its health and performance.

- **[CrystalDiskInfo](https://crystalmark.info/en/software/crystaldiskinfo/)** is a utility used to monitor the health of hard drives and solid-state drives. it can display various attributes of the drive, such as temperature, power-on hours, and the number of times it has been powered on.

### networking and connectivity

- **[PuTTY](https://www.putty.org/)** is a free and open-source terminal emulator, serial console, and network file transfer application. it supports several network protocols, including SCP, SSH and Telnet.

- **[WinSCP](https://winscp.net/eng/index.php)** is a free and open-source sFTP, SCP, FTPs, and FTP client. its main function is secure file transfer between a local and a remote computer.

- **[TeamViewer](https://www.teamviewer.com/)** is a proprietary software application for remote control, desktop sharing, online meetings, web conferencing, and file transfer between computers.

- **[Wireshark](https://www.wireshark.org/)** is a free and open-source packet analyzer. it is used for network troubleshooting, analysis, software and communications protocol development, and education.

- **[ReAct.exe](https://www.d7xtech.com/free-software/react/)** is a small utility for windows activation that offers options like supressing activation prompts, opening the activation window from an easy panel and checking the activation status.

### windows terminal commands

```bash
# SYSTEM REPAIR & UPDATES

# scan and repair system files (tampering/corruption)
sfc.exe /SCANNOW

# restore from restore point
rstrui.exe

# fix windows update errors
DISM /online /cleanup-image /restorehealth

# open system properties
msconfig
```

```bash
# FILES & DISKS

# windows classic app uninstaller (compact list style)
appwiz.cpl

# disk management
diskmgmt.msc
```

```bash
# WINDOWS ACTIVATION

# activate license by phone
slui 4

# activate license by product key
slmgr.vbs /ipk <valid product key>

# uninstall product key and go back to trial state
slmgr.vbs /upk

# clear product key from registry
slmgr.vbs /cpky

# view license info
slmgr.vbs /dlv

# show license expiry
slmgr.vbs /xpr
```

## linux

### files and data

- **[GParted](https://gparted.org/)** is a free partition editor for graphically managing your disk partitions.

### malware removal and security

todo.

### data recovery and backup

- **fsck** is a built-in command-line utility that can be used to check and repair filesystems, often able to recover data from bad sectors even when other tools fail. sometimes useful on other operating systems as well, if booted from a live cd.

- **[TestDisk](https://www.cgsecurity.org/wiki/testdisk)** is powerful free data recovery software. it was primarily designed to help recover lost partitions and/or make non-booting disks bootable again when these symptoms are caused by faulty software, certain types of viruses, or human error.

### specs, monitoring and hardware health

todo.

### networking and connectivity

- **[Nmap](https://nmap.org/)** is a free and open-source network scanner. it is used to discover hosts, ports and services on a computer network by sending packets and analyzing the responses.

### linux terminal commands

todo.
