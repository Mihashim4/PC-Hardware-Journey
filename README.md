## ⚠️ Important Note About the HDD Swap

The HDD used in this project already had Windows installed on it from another system.  
Because of that, the PC needed some time to properly recognize and configure the drive after the swap.

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
## 🎬 Related Video

[Watch the Video](https://youtu.be/eTOuDSbe9-w?si=OGK9eoejmoF5Dr6o)

---
