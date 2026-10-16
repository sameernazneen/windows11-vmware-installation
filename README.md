# Windows 11 Installation on VMware Workstation Pro

A step-by-step guide to downloading the Windows 11 ISO, creating a virtual machine, configuring its hardware, and installing Windows 11 using VMware Workstation Pro.

## 📌 Project Type

Lab Setup | Virtualization | Windows Deployment | IT Support

## 🧰 Tools and Technologies

- VMware Workstation Pro
- Windows 11 ISO
- Virtual machine configuration
- Virtual disk management
- Virtualization technology (Intel VT-x / AMD-V)

## 📖 Overview

This project documents the process of setting up a Windows 11 virtual machine using VMware Workstation Pro. It covers downloading the Windows 11 ISO, creating and configuring a virtual machine, attaching the ISO, installing the operating system, and completing the initial setup.

Screenshots are included to demonstrate the installation workflow and key configuration steps.

## ⬇️ Part 1: Download Windows 11 ISO

### Step 1: Visit the Official Microsoft Website

Visit the official [Windows 11 download page](https://www.microsoft.com/software-download/windows11).

![Windows 11 Download Page](images/01-windows_download.png)

### Step 2: Select the Windows 11 ISO

Navigate to the section for downloading the Windows 11 disk image (ISO).

Select the appropriate Windows 11 ISO edition, choose your preferred language, and download the 64-bit ISO file.

### Step 3: Verify the Download

Confirm that the ISO file has downloaded successfully and note its storage location.

![Downloaded Windows 11 ISO](images/10-iso-image.webp)

## ⚙️ Part 2: Create a New Virtual Machine

### Step 4: Create a New Virtual Machine

1. Open VMware Workstation Pro.
2. Select **Create a New Virtual Machine**.
3. Choose **Typical (recommended)**.
4. Continue through the setup wizard.

![Create a New Virtual Machine](images/02-creat-vm.webp)

### Step 5: Configure the Virtual Machine

Follow the wizard to configure the virtual machine and select the operating system installation options.

![Virtual Machine Configuration](images/03-configuration.webp)

If using the option to install the operating system later, select it and continue.

![Install Operating System Later](images/04-oslater.webp)

### Step 6: Select the Guest Operating System

Choose:
- Guest operating system: Microsoft Windows
- Version: Windows 11 x64

The available options may vary depending on your VMware Workstation version.

![Guest Operating System Selection](images/05-guest-os.webp)

### Step 7: Choose the Virtual Machine Name and Location

Enter a descriptive name, such as `Windows 11 VM`, and choose a suitable storage location.

![Virtual Machine Location](images/06-location.webp)

### Step 8: Allocate Virtual Disk Space

Choose a virtual disk size appropriate for the installation. A 60 GB virtual disk is a practical starting point for this lab, although more space may be needed for updates and additional applications.

Choose whether to store the virtual disk as a single file or split it into multiple files.

![Virtual Disk Size](images/07-disk-size.webp)

## 🔧 Part 3: Configure Virtual Hardware

### Step 9: Customize Hardware

Before starting the virtual machine, review its hardware settings.

Suggested starting configuration:
- Memory: 4 GB minimum; 8 GB or more is preferable when available.
- Processor: 2 virtual processor cores as a starting point.
- Virtual disk: 60 GB or more.
- Network adapter: Select the network mode appropriate for your lab.

The actual allocation should depend on the host computer's available resources.

![VM Hardware Configuration](images/08-hardware-configuration.webp)

### Step 10: Attach the Windows 11 ISO

Open the virtual machine settings and locate the CD/DVD drive.

1. Select **Use ISO image file**.
2. Browse to the downloaded Windows 11 ISO.
3. Select the correct ISO file.
4. Confirm the settings.

![Attach Windows 11 ISO](images/09-iso-attaching.webp)

## 🪟 Part 4: Install Windows 11

### Step 11: Start the Virtual Machine

Power on the virtual machine and boot from the Windows 11 installation media.

![Windows Installation](images/11-windows-installation.webp)

### Step 12: Enter the Product Key

Enter a valid product key if available. Otherwise, select **I don't have a product key** if that option is offered.

Activation may be required later, depending on your license.

![Windows Product Key Screen](images/12-product-key.webp)

### Step 13: Select the Windows Edition

Select the edition appropriate for your license and intended use.

![Windows 11 Edition Selection](images/13-windows11pro.webp)

### Step 14: Accept the License Terms

Review and accept the applicable license terms to continue.

![Windows License Agreement](images/14-agreement.webp)

### Step 15: Choose the Installation Type

Select **Custom: Install Windows only (advanced)** when performing a clean installation on the new virtual machine.

![Custom Windows Installation](images/15-custom-install-windows.webp)

### Step 16: Configure Windows Setup

Follow the installation wizard and proceed through the Windows setup screens.

![Windows Setup](images/16-windows-setup.webp)

### Step 17: Select the Virtual Disk

Select the intended virtual disk or unallocated space for Windows installation. Double-check that you are working with the virtual machine's disk.

![Windows Disk Partition Selection](images/17-disk-partition.webp)

### Step 18: Wait for Installation

Allow Windows to copy files, install features, and restart as required. Installation time depends on the host computer's performance and the virtual machine configuration.

![Installing Windows](images/18-installing-windows.webp)

## 🌐 Part 5: Complete the Initial Setup

### Step 19: Configure Windows Settings

Complete the initial setup screens, which may include:
- Region and keyboard layout
- Network connection
- Microsoft account or available local account options
- Privacy and device settings

![Windows Initial Settings](images/19-settings.webp)

### Step 20: Verify the Windows 11 Virtual Machine

After setup, start the virtual machine and confirm that Windows loads correctly.

![Windows 11 Virtual Machine](images/20-windowsvm.webp)

### Step 21: Final Verification

Review the final Windows environment and confirm that the virtual machine is ready for the next stage of configuration.

![Final Windows 11 Screen](images/21-final-windows.webp)

## 🛠️ Part 6: VMware Tools

Where supported and applicable, install VMware Tools from the VMware Workstation menu:

1. Select **VM → Install VMware Tools**.
2. Follow the installer instructions inside the guest operating system.
3. Restart the virtual machine if prompted.

VMware Tools can improve display integration, mouse handling, and other supported guest features.

## 🎯 Skills Demonstrated

This project documents practical work with:
- Virtual machine creation and configuration
- Windows 11 ISO selection and attachment
- Virtual CPU, memory, disk, and network settings
- Operating system installation
- Initial Windows configuration
- Basic virtualization troubleshooting

## 🚀 Future Improvements

- Document VMware Tools installation and verification.
- Add troubleshooting notes for common installation errors.
- Document verified network connectivity and host-to-guest communication.
- Expand the environment with additional operating systems for IT support and cybersecurity practice.

## 👨‍💻 Author

**Sameera Nazneen**

Aspiring IT Support Professional | Cybersecurity Learner
