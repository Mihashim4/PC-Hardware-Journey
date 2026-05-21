# 💻 PC Hardware Journey – HDD Swap Upgrade

Welcome to my PC Hardware Journey project!  
This repository showcases the process of upgrading and swapping a Hard Disk Drive (HDD) in a desktop PC setup.

This project is part of my learning experience in computer hardware, PC maintenance, and system upgrades.

---

## 📖 About The Project

In this project, I performed an HDD replacement/upgrade on my PC and documented the complete process.

### 🎯 Goals of This Project

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
| Screwdriver | Cabinet & HDD Installation |
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
<img width="2436" height="1080" alt="1000078410" src="https://github.com/user-attachments/assets/59fc90dc-7fbc-4ab1-8f60-825c41434923" />


--

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

<img width="2436" height="1080" alt="1000078411" src="https://github.com/user-attachments/assets/340c4457-cc7e-4f0a-8e9f-0d9e516b4dbc" />

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
<img width="2436" height="1080" alt="1000078412" src="https://github.com/user-attachments/assets/1ea4eaf0-b7cb-4a79-9ccd-7e5360310df7" />

---

## ⚠️ Important Note About the HDD Swap

The HDD used in this project already had Windows installed on it from another system.  
Because of that, the PC needed some time to properly recognize and configure the drive after the swap.

<img width="2436" height="1080" alt="1000078422" src="https://github.com/user-attachments/assets/22186e44-13c0-417f-80a3-057b8664ba7e" />

During the first boot, the system showed minor glitches and delays while:
- Detecting the hardware
- Loading drivers
- Configuring boot settings
- Adjusting to the new PC environment

This is normal when moving a Windows-installed HDD between different computers or motherboards.

### 🔧 Possible Issues You May Face
- Slow first boot
- Driver installation errors
- Windows activation warning
- Boot configuration problems
- Temporary lag or freezing

### ✅ How It Was Fixed
- Restarted the PC multiple times
- Allowed Windows to install required drivers
- Checked BIOS boot priority
- Reconnected SATA cables properly
- Waited for Windows setup/configuration to complete

After the setup process finished, the HDD worked normally on the system.

---

## 💡 Alternative Option – Formatting the HDD

Another possible solution is formatting the HDD before using it on a different PC.

Formatting removes:
- Previous Windows installation
- Old drivers
- System configuration conflicts
- Unnecessary files

This allows the drive to work like a fresh storage device and can reduce boot or compatibility issues.

### ⚠️ Warning
Formatting the HDD will permanently erase all existing data, including:
- Windows installation
- Applications
- Personal files
- Documents and media

Always create a backup before formatting the drive.

---

## 🖥️ Formatting the HDD Using CMD / Terminal

Windows provides built-in tools to format a drive using Command Prompt.

### 🔹 Method 1 – Using DiskPart (CMD)

Open Command Prompt as Administrator and type:

```bash
diskpart
```
Then follow these commands:
```
list disk
```
Find the HDD number and select it:
```
select disk X
```
Replace X with the correct disk number.

Clean the drive:
```
clean
```
Create a new partition:
```
create partition primary
```
Format the drive:
```
format fs=ntfs quick
```
Assign a drive letter:
```
assign
```
Exit DiskPart:
```
exit
```

---

🔹 Method 2 – Using Windows File Explorer

1. Open This PC


2. Right-click the HDD


3. Select Format


4. Choose:

File System: NTFS

Quick Format: Enabled



5. Click Start




---

⚠️ Important Reminder

Before formatting:

Verify the correct drive is selected

Backup important files

Disconnect unnecessary storage devices if needed


Formatting the wrong drive may result in permanent data loss.


---

## 🎥 Video Demonstration

This project is also demonstrated through a Tamil tech video showing the HDD transfer and testing process.

▶️ Watch here:
https://youtu.be/eTOuDSbe9-w

---
## 📚 What I Learned

Through this project, I learned:

- Basic HDD handling
- Storage device connections
- Windows boot behavior
- SATA cable usage
- Practical PC troubleshooting
- Hardware experimentation

---
## 🚀 Future Plans

- SSD upgrade experiments
- Linux installation projects
- PC cleaning and maintenance
- Multi-drive testing
- Hardware benchmarking


---
