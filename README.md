# Windows 11 Installation Lab

This project documents my hands-on lab installing **Windows 11 Pro** inside **Oracle VirtualBox**. I stepped through the full OS installation wizard: selecting language and keyboard settings, choosing the edition, partitioning the virtual disk, and confirming the final install.

## Objectives

- Boot from a Windows 11 ISO in a VirtualBox VM
- Configure language, time, currency and keyboard layout
- Choose the installation option (keep nothing vs. repair)
- Select the Windows 11 edition (Home vs Pro)
- Partition unallocated disk space for installation
- Verify readiness and begin installation

## Technologies Used

- **Oracle VirtualBox** (running on your host machine)
- **Windows 11 ISO**
- **Virtual Machine hardware**: 2 CPUs, 4 GB RAM, 60 GB disk (example)

## Skills Demonstrated

- Operating system installation and configuration
- Understanding virtualization vs. bare‑metal installs
- Disk partitioning within an OS installer
- Interacting with VirtualBox menus (e.g. sending Ctrl‑Alt‑Del)
- Choosing appropriate OS editions and license options

## What I Learned

- The difference between **Windows 11 Home**, **Pro**, **Education**, etc., and when to choose each.
- How to properly partition a virtual disk (create partition on unallocated space).
- Why product keys and licensing matter even in lab environments.
- That VirtualBox requires special key combinations (e.g. sending Ctrl‑Alt‑Del) to interact with the VM.
- How to follow an OS installer from language selection through to installation progress.

## Screenshots

See the `screenshots/` folder for step‑by‑step images, including:

- **language-settings.png** – choosing English (US) for language and currency  
- **keyboard-settings.png** – selecting the US keyboard layout  
- **setup-options.png** – choosing _Install Windows 11_ versus _Repair my PC_  
- **product-key.png** – product key entry screen (can skip by selecting “I don’t have a product key”)  
- **select-image.png** – selecting _Windows 11 Pro_ from the list of editions  
- **partition-select.png** – choosing the unallocated 60 GB disk and creating a partition  
- **ready-to-install.png** – final summary screen showing selected options  
- **installation-progress.png** – installation running at ~7 % (VirtualBox window)  
