# Cyber Security Lab Setup Guide

This repository helps beginners set up a personal cybersecurity lab using **VirtualBox** and **Kali Linux**. It is designed for those who want to learn ethical hacking, penetration testing, and cybersecurity tools in a safe and isolated environment.

---

## 🔧 What You'll Learn

- Installing VirtualBox on your system
- Downloading and extracting Kali Linux ISO/VM image
- Setting up Kali Linux in VirtualBox
- Configuring basic settings for networking and performance
- Starting your first ethical hacking lab

---

## 🖥️ Installing VirtualBox

1. Visit the official VirtualBox website: [https://www.virtualbox.org/](https://www.virtualbox.org/)
2. Click on **Downloads** and choose your operating system (Windows/Linux/macOS).
3. Download the installer and run the setup file.
4. Follow the on-screen instructions (keep default settings if unsure).
5. Once installed, launch VirtualBox from your desktop or start menu.
6. Optional: Install the Extension Pack for enhanced features like USB 2.0/3.0 support.

---

## 🐱‍💻 Downloading & Setting Up Kali Linux in VirtualBox

1. Go to the official Kali Linux downloads page: [https://www.kali.org/get-kali/](https://www.kali.org/get-kali/)
2. Download either:
   - The **ISO image** (for manual setup), or
   - The **VirtualBox prebuilt image** (recommended for beginners)
3. If you downloaded the ISO:
   - Open VirtualBox → Click **New** → Name it "Kali Linux"
   - Set Type: **Linux**, Version: **Debian (64-bit)**
   - Allocate RAM (at least 2GB recommended)
   - Create a virtual hard disk (20GB or more)
   - In **Settings > Storage**, mount the Kali ISO under "Empty" optical drive
4. If you downloaded the prebuilt VM:
   - Extract the `.7z` or `.zip` file using tools like WinRAR or 7-Zip
   - Open VirtualBox → **File > Import Appliance** → Choose the `.ova` file
   - Click **Next > Import**
5. After setup, click **Start** to boot into Kali Linux

---

## 🧠 Notes

- Default Kali login credentials:  
  - **Username:** `kali`  
  - **Password:** `kali`
- Enable "Bidirectional" clipboard and drag & drop in **Settings > General > Advanced**
- To go full screen, install **Guest Additions** via the Devices menu inside Kali

---

## 📂 Repository Structure (Optional)

