# Installing Kali Linux in Oracle VM VirtualBox

## Overview

This guide explains how to install Kali Linux in Oracle VM VirtualBox on a Windows computer. It covers downloading the required software, creating the virtual machine, installing Kali Linux, and verifying that the installation completed successfully.

## Objectives

By the end of this guide, you will be able to:

- Download Kali Linux.
- Install Oracle VM VirtualBox.
- Create a virtual machine.
- Install Kali Linux.
- Boot into Kali Linux successfully.

## Prerequisites

Before you begin, ensure you have:

- A Windows computer
- Administrator privileges
- At least 8 GB RAM (16 GB recommended)
- At least 40 GB of free disk space
- A stable internet connection

## Required Downloads

- Oracle VM VirtualBox
- Kali Linux Installer ISO

## Installation Steps

### Step 1: Install Oracle VM VirtualBox

Download and install Oracle VM VirtualBox using the default installation settings.

### Step 2: Download Kali Linux

Download the latest Installer ISO from the official Kali Linux website.

### Step 3: Create a Virtual Machine

1. Open VirtualBox.
2. Select **New**.
3. Enter a name for the virtual machine.
4. Select Linux as the operating system.
5. Allocate memory.
6. Create a virtual hard disk.

### Step 4: Attach the ISO

Open **Settings → Storage** and attach the downloaded Kali Linux ISO file.

### Step 5: Start the Installation

Start the virtual machine and follow the installation wizard.

### Step 6: Complete Installation

Restart the virtual machine after installation and remove the ISO if prompted.

## Verification

The installation is successful if the Kali Linux login screen appears.

## Troubleshooting

### Virtual machine will not start

- Verify virtualization is enabled in BIOS.
- Ensure sufficient RAM is allocated.

### Boot device not found

Confirm that the Kali Linux ISO is attached correctly.

### Slow performance

Increase available RAM and CPU cores if your system allows.

## Conclusion

You have successfully installed Kali Linux in Oracle VM VirtualBox and are ready to begin using the operating system.
