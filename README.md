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

1. Visit the official Microsoft Windows 11 download page  
2. Navigate to **Download Windows 11 Disk Image (ISO)**  
3. Select **Windows 11 (multi-edition ISO)**  
4. Choose your preferred language  
5. Click **64-bit Download**  
6. Verify the ISO file in your system  

> ⚠️ Always download from official Microsoft sources to ensure security and authenticity.

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
- Browse and select the Windows 11 ISO  
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

Click **Close → Finish**

---

## ▶️ Step 7: Start Virtual Machine
- Select the VM  
- Click **Power on this virtual machine**

---

## 🪟 Step 8: Install Windows 11
- Select language, time, and keyboard  
- Click **Install Now**

---

## 🔑 Step 9: Product Key
- Enter product key OR  
- Select **I don’t have a product key**

---

## 📦 Step 10: Select Edition
- Choose desired Windows 11 edition  
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
- Configure region and keyboard  
- Connect to network  
- Create Microsoft or local account  
- Adjust privacy settings  

---

## 🛠️ Step 15: Install VMware Tools
- Go to **VM → Install VMware Tools**  
- Run installer inside VM  
- Restart system  

### Benefits:
- Better graphics performance  
- Smooth mouse movement  
- File sharing between host and VM  

---

## ✅ Conclusion
This lab successfully demonstrates:
- Virtual machine creation  
- Windows 11 installation  
- System configuration in a virtual environment  

This setup can be used for testing, development, and cybersecurity labs.

---

## 🚀 Future Improvements
- Automate setup using scripts  
- Integrate with Active Directory lab  
- Use for malware analysis environment  

---

## 👨‍💻 Author
Sameera Nazneen 
