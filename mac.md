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