# windows11-vmware-installation
Step-by-step Windows 11 installation on VMware Workstation Pro

## 📌 Project Type
Lab Setup / Virtualization / Windows Deployment

---

## 🧰 Tools & Technologies
- VMware Workstation Pro
- Windows 11 ISO
- Virtualization (Intel VT-x / AMD-V)

---

## 📖 Overview
This project demonstrates a complete step-by-step procedure to install Windows 11 on a virtual machine using VMware Workstation Pro. It includes ISO download, VM configuration, OS installation, and post-installation setup.

---

## ⬇️ Downloading Windows 11 ISO

### Step 1: Visit official Microsoft download page
Open a browser and navigate to the official Microsoft Windows 11 ISO download page.

![Windows 11 Download Page](screenshots/windows11-download.webp)

### Step 2: Navigate to ISO section
Scroll down to **Download Windows 11 Disk Image (ISO)**.

### Step 3: Select Windows 11 ISO
Choose **Windows 11 (multi-edition ISO)**.

### Step 4: Choose language and download
Select language and click **64-bit Download**.

### Step 5: Verify download
Ensure ISO file is properly downloaded in your system.

---

## ⚙️ Prerequisites
- VMware Workstation Pro installed  
- Windows 11 ISO file  
- Virtualization enabled in BIOS (Intel VT-x / AMD-V)  
- Minimum system requirements:
  - 8 GB RAM (recommended)
  - 2 CPU cores
  - 60 GB disk space  

---

## 🖥️ Step 1: Create a New Virtual Machine
- Open VMware Workstation Pro  
- Click **Create New Virtual Machine**  
- Select **Typical (recommended)**  
- Click **Next**

---

## 💿 Step 2: Mount ISO File
- Select **Installer disc image file (ISO)**  
- Browse and select Windows 11 ISO  
- Click **Next**

---

## 🧩 Step 3: Configure Operating System
- OS: Microsoft Windows  
- Version: Windows 11 x64  
- Click **Next**

---

## 📁 Step 4: Name and Location
- Name: `Windows 11 VM`  
- Choose storage location  
- Click **Next**

---

## 💾 Step 5: Allocate Disk Space
- Minimum: 60 GB  
- Choose:
  - Single file (better performance)  
  - Multiple files (easier transfer)  
- Click **Next**

---

## 🔧 Step 6: Customize Hardware
- RAM: 4 GB minimum (8 GB recommended)  
- CPU: At least 2 cores  
- Enable virtualization (VT-x / AMD-V)

### Processor Configuration
![CPU Setup](screenshots/processor.webp)

### Memory Configuration
![Memory Setup](screenshots/memory-vm.webp)

Click **Close → Finish**

![VM Ready](screenshots/ready-vm.webp)

---

## ▶️ Step 7: Start Virtual Machine
- Select the VM  
- Click **Power on this virtual machine**

![Start VM](screenshots/start-vm.webp)

---

## 🪟 Step 8: Install Windows 11
- Select language, time, and keyboard  
- Click **Install Now**

---

## 🔑 Step 9: Product Key
- Enter product key OR  
- Click **I don’t have a product key**

---

## 📦 Step 10: Select Edition
- Choose Windows 11 edition  
- Click **Next**

---

## 📜 Step 11: License Agreement
- Accept terms  
- Click **Next**

---

## 🧹 Step 12: Installation Type
- Select **Custom: Install Windows only (Advanced)**

---

## 💽 Step 13: Disk Selection
- Select virtual disk  
- Click **Next**

System will install and restart automatically.

---

## 🌐 Step 14: Final Setup
- Region and keyboard selection  
- Network setup  
- Microsoft or local account  
- Privacy settings  

---

## 🛠️ Step 15: Install VMware Tools
- Go to **VM → Install VMware Tools**  
- Install inside VM  
- Restart system  

### Benefits:
- Better performance  
- Smooth mouse integration  
- File sharing between host and VM  

---

## ✅ Conclusion
This lab successfully demonstrates:
- Virtual machine creation  
- Windows 11 installation  
- System configuration in a virtual environment  

It can be used for:
- IT training  
- Cybersecurity labs  
- Software testing environments  

---

## 🚀 Future Improvements
- Automate setup using scripts  
- Integrate Active Directory lab  
- Use for malware analysis environment  

---

## 👨‍💻 Author
Sameera Nazneen
