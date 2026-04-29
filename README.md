# Linux Server Setup

# Overview
Basic setup of an Ubuntu Linux server using VirtualBox.

## Tools Used
- Oracle Virtual Box
- Ubuntu ISO

## Steps Performed

### 1. Environment Setup
- Downloaded Ubuntu ISO,
- Downloaded Oracle Virtual Box,

### 2. Installation
- Mounted the Ubuntu ISO,
- Determined system specs, RAM, CPU count, disk space,
and installed Ubuntu.

### 3. System Update
```bash
sudo apt update && sudo apt upgrade -y
```

### GUI Upgrade
```bash
sudo apt install ubuntu-desktop
sudo shutdown -r now
```

# Result
A working Ubuntu system running in VirtualBox with GUI enabled.
