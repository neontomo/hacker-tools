# disks and recovery

## commands

**fsck** is a built-in command-line util that checks and repairs filesystems with bad sectors. sometimes useful on other OSs if booted from a live CD. for example, fixing Windows from Linux live CD.

### dry-run scan for drive corruption
```sh
fsck -N
```

### fix all drives
```sh
# A = all
# s = skip drives marked as clean
fsck -As
```

### force fix drive
```sh
# change `sdaX` to actual drive
fsck -f /dev/sdaX
```

## apps

- **[gparted](https://gparted.org/)** is a free partition editor for graphically managing your disk partitions.

- **[testdisk](https://www.cgsecurity.org/wiki/testdisk)** is powerful free data recovery software. it was primarily designed to help recover lost partitions and/or make non-booting disks bootable again when these symptoms are caused by faulty software, certain types of viruses, or human error.