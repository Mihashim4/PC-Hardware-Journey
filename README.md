# 💻 PC Hardware Journey – HDD Swap Upgrade
---
Welcome to my PC Hardware Journey project!  
This repository showcases the process of upgrading and swapping a Hard Disk Drive (HDD) in a desktop PC setup.
---
This project is part of my learning experience in computer hardware, PC maintenance, and system upgrades.

---

## 📖 About The Project

In this project, I performed an HDD replacement/upgrade on my PC and documented the complete process.
---

The goal of this project was to:

- Learn PC hardware handling
- Understand HDD installation
- Practice safe computer maintenance
- Improve storage performance and management
- Explore internal PC components

---

## 🛠️ Hardware & Tools Used

| Hardware / Tool | Purpose |
|-----------------|---------|
| SATA HDD | Storage Device |
| SATA Data Cable | Data Transfer |
| SATA Power Cable | Power Supply |
| Screwdriver | Cabinet & HDD installation |
| Desktop PC | Testing Environment |

---

## ⚙️ HDD Swap Process

### 🔹 Step 1 – Shutdown the PC
- Turn off the computer completely
- Disconnect the power cable
- Press the power button for a few seconds

---

### 🔹 Step 2 – Open the Cabinet
- Remove the side panel screws
- Carefully open the cabinet

---

### 🔹 Step 3 – Locate the HDD
Find the existing hard drive mounted inside the drive bay.

---

### 🔹 Step 4 – Disconnect Cables
Remove:
- SATA Data Cable
- SATA Power Cable

---

### 🔹 Step 5 – Remove the Old HDD
- Unscrew the HDD
- Slide it out carefully

---

### 🔹 Step 6 – Install the New HDD
- Insert the new HDD into the bay
- Secure it with screws

---

### 🔹 Step 7 – Connect the Cables
Reconnect:
- SATA Data Cable
- SATA Power Cable

---

### 🔹 Step 8 – Close the Cabinet
- Reattach the side panel
- Tighten the screws properly

---

### 🔹 Step 9 – Boot & Verify
- Power on the PC
- Check BIOS or Operating System detection

_____________________________________________________

### 🎬 Related Video

[Watch the Video](https://youtu.be/eTOuDSbe9-w?si=OGK9eoejmoF5Dr6o)

_____________________________________________________

## ⚠️ Important Note About the HDD Swap

The HDD used in this project already had Windows installed from another PC.  
Because of this, the system needed extra time to properly detect and configure the drive after installation.

During the first boot, the PC experienced:
- Driver loading delays
- Boot configuration adjustments
- Minor lag and temporary glitches

This is normal when transferring a Windows-installed HDD between different systems.

### ✅ Fixes Performed
- Restarted the PC multiple times
- Allowed Windows to install drivers
- Checked BIOS boot priority
- Verified SATA connections

After configuration completed, the HDD worked normally.

---

## 💡 Alternative Solution – Format the HDD

Another option is formatting the HDD before using it on another PC.

Formatting removes:
- Old Windows installation
- Driver conflicts
- Previous system configurations

### 🖥️ Formatting Using CMD

Open Command Prompt as Administrator and run:

```cmd
diskpart
list disk
select disk X
clean
create partition primary
format fs=ntfs quick
assign
exit

> Replace X with the correct HDD number.



⚠️ Warning

Formatting permanently deletes all data on the drive.
Always backup important files before proceeding.

This version:
- Looks cleaner on GitHub
- Has less scrolling
- Easier for users to read
- More professional
- Better mobile viewing
- Keeps only useful information

Your repo already looks good — it just needed cleaner formatting.0
