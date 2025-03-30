# Goodix Fingerprint Drivers for Linux (or at least Debian)

## Disclaimer
This repository is intended to preserve the functionalities of the mentioned devices.
Every intellectual property of the software is owned by the authors (Goodix most likely).

## Compatibility

### Tested

This repository has been tested on Ubuntu 24.04 and 23.10.

### Untested but may work

Debian based systems

### Tested and doesn't work

Garuda Linux

### Untested and probably won't work

Arch based systems

## Guide to the Repository

### Install

Please chose one of the paths listed in the next paragraphs.

Quick and dirty TLDR for Debian/Ubuntu:

- See Supported Devices paragraph
- Clone this repo
    sudo apt install ./selected.deb

### Precompiled .deb packages

You should (or could) select this if you are on Debian/Ubuntu

### Extracted

Contains both the extracted data folder of the above mentioned packages (useful for experimenting)

You can `git clone https://github.com/tcsenpai/goodix-debian-linux-drivers-fingerprint-by-dell`, navigate to `extracted` and your version (see #Supported devices) and copy the contained files in the exact same file structure in your system (creating folders if needed).

Note: this method is quite experimental, please back up anything you may overwrite.

### Bare_so_files

I don't know if they are useful but hey, less packaging!

## Supported devices

To understand which version you need, pleae execute:

```
lsusb
```
and look for the Fingerprint line, or anything applicable. It should contain a string like the below ones.

### 0.0.4

- 27c6:538c
- 27c6:533c
- 27c6:530c
- 27c6:5840

### 0.0.9

- 27c6:550a


## Issues and PR

Are more than welcomed!

