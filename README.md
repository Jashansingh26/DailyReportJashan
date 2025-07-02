# Daily Report :
# DAY 1️⃣ : 📖🖊
On the first day of training , first of all mam Priyanka mam introduced us with the faculty members of our department . Then HOD mam of our department told us about the future projects , terms and conditions that we have to keep in our mind in the future . Also they explained us about the subjects that we have to study in the next semester , which subjects can we select for specialisation in fifth and sixth semester. 

After that , we had a training session of about 3 hours . In the session , first of all mam introduced us with our first topic of the training which is Fundamentals of Linux . Then mam told us about the history of Linux . Then we get to know that what are its applications , in which companies it is used .Then mam explained us about product based companies , service based ompanies and startups. Then mam told us about differnce between Linux and Windows and what are the benefits of using Linux over Windows . Then we discussed about the career options in our field .

After that we learned the concept of booting and its types .

INSTALLATION OF LINUX - After that we had to install linux on our laptops. For this purpose we downloded Oracle Virtual Box 7.1.10. and Ubuntu (Linux) 24.04.2.

![Image](https://github.com/user-attachments/assets/76c47105-5c20-4122-9900-8b4c90b87e79)

# DAY 2️⃣ :
On the second day , first of all we revised the topics covered on the first day. 

Then we started learning about KERNEL . Kernel refers to the core component of an operating system. It manages the system's resources and allows communication between hardware and software. Then we learned about shell and it it works as an interface between user and Kernel . Mam explained this in a very interesting way with the help of following diagram .
![Image](https://github.com/user-attachments/assets/3265cd12-f5a2-4a40-aeca-826d7ceca14f)

Also we understood four types of shell i.e sh,bash,csh,ksh and two categories of shell i.e command line shell and graphical shell . Then we also get to know about file system structure.

![Image](https://github.com/user-attachments/assets/3a44e1ab-d939-4157-8c79-a0bb3ed3b66c)

#COMMANDS 
We practised various commands such as ls , date , mkdir , whereis  , whatis , cat , cp , cd and many more . Here are some snapshots of the commands that i have practised .
| Command | Description |
|---------|------------ |
| ls | List files and directories |
| date |Show current date and time|
| whereis | Locate binary, source, and man files|
| whatis | Display brief command description|
| mkdir | Create new directory|
| pwd | Show current directory path |
| mv | Move or rename files/directories |
| cd | Change directory |
| cp | Copy files or directories |
| whoami | Show current logged-in username |
| cat | Display file contents |

| touch | Create empty file or update timestamp |

![Image](https://github.com/user-attachments/assets/af3d6199-3f66-4d4a-85fe-7ea4257440b5)

![Image](https://github.com/user-attachments/assets/3e3a3aa7-9a52-45ca-add1-ae630720e88e)

![Image](https://github.com/user-attachments/assets/a3f916ed-959c-439e-a3e5-2275dcae1b5d)

![Image](https://github.com/user-attachments/assets/02dcbf4e-c966-43af-9dfa-b85a4ecef8f7)

![Image](https://github.com/user-attachments/assets/deb3bb2f-b82f-4f97-a008-7ade88ccea90)

# DAY 3️⃣ :
We started day 3 by revising some important terms and topics of previous two days which are as follows :
 # 🖥️ Dual Boot
 - Dual booting allows a computer to run two different operating systems (OSes) on the same machine.

- Upon startup, users can choose which OS to boot into.

- Common setups include Windows/Linux .

# 📀 ISO File
- An ISO file is a disk image that contains the complete contents of a CD, DVD, or other optical media

- These are commonly used to distribute Linux distributions and other bootable software.

# 🧱 Bare Metal Installation
- A bare metal installation involves installing an operating system directly onto a computer’s hardware, without any virtual box .

- This is typically used for full hardware access.

# 💼 VMware
- VMware is a commercial virtualization platform known for its robust, enterprise-level features.

- It offer strong performance, and professional support, making it ideal for production environments.

# 🔧 VirtualBox
- VirtualBox is a free and open-source virtualization tool developed by Oracle.
 
- Best suited for personal use, development, and testing.

# 🗂️ Partitioning Schemes
- Partitioning involves dividing a hard disk into multiple sections, called partitions.

- Each partition can house a separate file system or OS.

Common schemes include:

- MBR (Master Boot Record) – older, supports up to 4 primary partitions, use bios .

- GPT (GUID Partition Table) – newer, supports more partitions and is compatible with UEFI systems.

# 🔐 File and Directory Permissions in Linux
- Linux uses a permission model to control who can read, write, or execute files and directories.
- 
- *chmod* - chmod stands for "change mode", and it's a command used in Unix/Linux systems to set or modify the permissions of a file or directory.
- Syntax - chmod [who][operator][permission] [file]
- 
Components:
- Who:

u = user (owner)

g = group

o = others

a = all (u+g+o)

- Operator:

+ = add permission

- = remove permission

= = set exact permission

- Permission:

r = read

w = write

x = execute

# Redirection in Linux
Redirection in Linux means sending the input or output of a command to a file or another command, instead of the default input/output (usually the terminal).

📤 Output Redirection
| Type	| Symbol	| Example	| Description |
|------|--------|---------|-------------|
| Output	| >	| echo "Hello" > file.txt	| Writes "Hello" to file.txt (overwrites it) |
| Append	| >>	| echo "World" >> file.txt	| Appends "World" to the end of file.txt |

📥 Input Redirection
| Type	| Symbol	| Example	| Description |
|------|--------|---------|-------------|
| Input |	<	| wc -l < file.txt	| Reads file.txt as input to wc -l |

# 🔗 Pipes in Linux (|)
A pipe takes the output of one command and sends it as input to another command.

- Syntax
 
command1 | command2
command1 → generates output

command2 → uses that output as its input

- Example:
 
ls | sort
ls lists files

sort sorts the file names alphabetically

So, this command lists and sorts the files in the current directory.

# PRACTICE PROGRAMS
## Program 1 :
- To find the greater between two numbers :
  
![Image](https://github.com/user-attachments/assets/1c6673a3-a6b4-47ad-905c-98679be5d700)

![Image](https://github.com/user-attachments/assets/54a1d67d-2c3c-4736-82f2-daff542e76af)

- To display various variables :
  
![Image](https://github.com/user-attachments/assets/bab98615-0971-4235-bbc8-ac90e9f262a7)

![Image](https://github.com/user-attachments/assets/3b8921fb-8299-49e2-ba39-8197d7e43750)

- To print a multiplication table of a number :
  
![Image](https://github.com/user-attachments/assets/0c8e9a56-e468-4013-8a50-aa2e296b4342)

![Image](https://github.com/user-attachments/assets/9ea652af-c40e-47dd-81b5-ced894433142)

# DAY 4 :
### PC HARWARE :
#  Motherboard (Main Circuit Board)

The **motherboard** is the central printed circuit board (PCB) in a computer. It connects and allows communication between all critical components such as the CPU, RAM, storage devices, GPU, and power supply.

![WhatsApp Image 2025-06-30 at 11 38 07_2c833e5c](https://github.com/user-attachments/assets/87b796a6-0d09-4f03-9d42-82209fb2fc5b)

##  Key Components Found on the Motherboard

| Component | Description |
|-----------|-------------|
| **CPU Socket** | The slot where the central processing unit (CPU) is installed. |
| **RAM Slots (DIMM Slots)** | Sockets used to install RAM (memory) modules. |
| **24-pin and 8-pin Power Connectors** | Supply electrical power to the motherboard and CPU. |
| **SATA Ports** | Connect hard drives and solid-state drives (SSDs). |
| **IDE Connector** | Used to connect legacy hard drives or optical drives. |
| **AGP / PCI / PCIe Slots** | Expansion slots for graphics cards (GPU), sound cards, network cards, etc. |
| **BIOS/UEFI Chip** | Stores low-level firmware needed to boot the system and configure hardware. |
| **USB Ports** | Connect external devices like a keyboard, mouse, flash drive, etc. |
| **Audio, VGA, HDMI, and Modem Ports** | Provide audio and video output, and modem connectivity. |
| **Fan Connectors** | Supply power and control to system or CPU cooling fans. |
| **Heat Sink Area** | Mounting point for a heat sink or cooler to dissipate CPU heat. |
| **CMOS Battery** | Keeps the BIOS settings (like date/time) when the system is powered off. |

## Various components of CPU 
![WhatsApp Image 2025-06-30 at 11 37 17_10a3fcc6](https://github.com/user-attachments/assets/bdd6b9a0-63be-4153-a6d4-6e26bdddc0dd)

| Component | Description |
|-----------|-------------|
| **Expansion Slots** | Allow installation of additional components like graphics cards, sound cards, or network cards to expand the system’s capabilities. |
| **Fan** | Helps regulate the system’s temperature by expelling hot air and drawing in cool air to prevent overheating. |
| **Optical Drive** | Used to read from and write to CDs and DVDs. Commonly used for media or software installation (less common today). |
| **Connectors** | Includes USB, audio, HDMI, and other ports on the case to connect external devices like a keyboard, mouse, or speakers. |
| **Power Supply Unit (PSU)** | Converts AC power from a wall outlet into low-voltage DC power to run internal components. |
| **Hard Disk Drive (HDD)** | Primary storage device for the operating system, files, and installed programs. May be replaced or supplemented by SSDs. |

## Difference Between Hard Disk, RAM, and Cache Memory

| Feature | Hard Disk (HDD/SSD) | RAM (Random Access Memory) | Cache Memory |
|--------|----------------------|-----------------------------|---------------|
| **Type** | Non-volatile storage | Volatile memory | Volatile memory |
| **Speed** | Slowest among the three | Faster than HDD | Fastest memory |
| **Purpose** | Stores OS, software, and files permanently | Temporarily holds data and programs currently in use | Temporarily stores frequently accessed data by the CPU |
| **Location** | Separate storage device | Installed on the motherboard | Built into or very close to the CPU |
| **Data Loss on Power Off** | No | Yes | Yes |
| **Size (Typical)** | Hundreds of GB to several TB | 4 GB to 64 GB | Few MBs to tens of MBs |
| **Cost per GB** | Lowest | Moderate | Highest |

### FILE COMPRESSION :

## What is File Compression?

**File compression** is the process of reducing the size of files to save disk space or make them faster to transfer over networks. Compression works by encoding data more efficiently, often by removing redundancy.

Compressed files can later be **decompressed (or uncompressed) .

##  gzip, gunzip, and gzip -k Commands

| Command      | Description                                    | Effect on Original File      | Output File          |
|--------------|------------------------------------------------|-----------------------------|----------------------|
| `gzip file`   | Compresses the file using gzip                  | Original file is deleted     | `file.gz`            |
| `gunzip file.gz` | Decompresses the gzip compressed file          | Original `.gz` file is deleted | Decompressed `file`  |
| `gzip -k file` | Compresses the file but keeps the original file | Original file is **kept**    | `file.gz` and original `file` |

![WhatsApp Image 2025-06-30 at 22 15 13_e8281f4a](https://github.com/user-attachments/assets/2c8d826c-2eeb-4b48-816e-5125f3e1a822)

### WILDCARDs : 

## Wildcards in File Matching

| Wildcard  | Meaning                                  | Example                 | Matches                                    |
|-----------|------------------------------------------|-------------------------|--------------------------------------------|
| `*`       | Matches zero or more characters           | `*.txt`                 | All files ending with `.txt` (e.g., `a.txt`, `file.txt`) |
| `?`       | Matches exactly one character              | `file?.txt`             | `file1.txt`, `fileA.txt`, but not `file10.txt` |
| `[a-z]`   | Matches any one character in the specified range | `file[0-9].txt`         | `file0.txt`, `file1.txt`, ..., `file9.txt` |

![WhatsApp Image 2025-06-30 at 22 15 13_c6b044a0](https://github.com/user-attachments/assets/0dbd257f-9c00-4cd9-b40f-d77c1742e9c8)

## ESCAPING CHARACTERS :
## Common Escape Characters

| Escape Sequence | Meaning                 | Example Usage                | Output / Explanation             |
|-----------------|-------------------------|------------------------------|---------------------------------|
| `\n`            | Newline (line break)    | `Hello\nWorld`                |  Hello World (prints on two lines)     |
| `\t`            | Horizontal tab          | `Hello\tWorld`                | `Hello    World` (tab space)    |
| `\\`            | Backslash character     | `C:\\Users\\Name`             | `C:\Users\Name`                 |
| `\"`            | Double quote character  | `He said, \"Hello\"`          | He said, "Hello"                |
| `\'`            | Single quote character  | `It\'s sunny`                 | It's sunny                     |


![WhatsApp Image 2025-06-30 at 22 15 13_e619f683](https://github.com/user-attachments/assets/b510bc68-2972-429d-8e70-27760e7265d2)

# DAY 5 : 
# 💾 Hard Disk

A **Hard Disk** (or Hard Disk Drive - HDD) is a non-volatile data storage device used in computers and other electronic devices. It stores digital data using magnetic storage and rotating platters.

Hard disks are used to store:
- Operating systems
- Software applications
- Files (documents, images, videos, etc.)
- Backup data

---

## Components of a Hard Disk

- **Platter**: Disk where data is magnetically stored.
- **Spindle**: Rotates the platters.
- **Read/Write Head**: Reads and writes data to the platter.
- **Actuator Arm**: Moves the head to the right location.
- **Controller Board**: Manages data flow between the hard disk and computer.

---

# 🔍 Types of Hard Disks


| Type       | Speed     | Cost   | Capacity | Moving Parts | Best For                  |
|------------|-----------|--------|----------|---------------|----------------------------|
| HDD        | Slow      | Low    | High     | Yes           | Bulk storage, backups     |
| SSD        | Fast      | High   | Medium   | No            | Laptops, OS drives        |
| SSHD       | Moderate  | Medium | High     | Yes + No      | Everyday users            |
| NVMe SSD   | Very Fast | High   | Medium   | No            | High-performance needs    |


### Common Reasons for slowing down of pc 

- **Too many startup apps** – Apps auto-start when your PC turns on, slowing it down.  
- **Background apps** – Programs running in the background use memory and slow things.  
- **Viruses/malware** – Bad software that sneaks in and makes your PC act slow or weird.  
- **Low RAM** – Not enough memory = lag when doing many things at once.  
- **Full or messy hard drive** – Less space or messy files = slower PC, especially on HDDs.  
- **Old hardware** – Older parts may not handle new software well.  
- **Too many browser tabs/extensions** – Eats up RAM and slows your PC.  
- **Overheating** – Hot PC slows itself down to cool off.  
- **Outdated system or drivers** – Old updates or drivers = poor performance.  
- **Low disk space** – Your PC needs free space to run smoothly.  
- **Fancy visuals** – Cool effects = more work for your PC.  
- **Heavy apps open** – Big programs running together slow things down.  
- **Broken system files** – Damaged files = errors or slowness.  
- **Unwanted apps** – Extra programs you don’t use can waste space and slow you down.  
- **Old or dying hard drive** – Old drives (especially HDDs) get slower over time.

 ### Common Reasons Why Your PC Might Be Slow (With Fixes)

- **Too many startup apps**  
  *Fix:* Disable unnecessary startup programs using Task Manager.

- **Background apps**  
  *Fix:* Close unused apps and background processes.

- **Viruses/malware**  
  *Fix:* Run a full scan with a good antivirus or Windows Defender.

- **Low RAM**  
  *Fix:* Upgrade your RAM if possible, or avoid running too many apps at once.

- **Full or messy hard drive**  
  *Fix:* Delete unused files, uninstall unused programs, and run Disk Cleanup.

- **Old hardware**  
  *Fix:* Upgrade hardware like RAM, SSD, or CPU if possible.

- **Too many browser tabs/extensions**  
  *Fix:* Close tabs you're not using and remove unnecessary extensions.

- **Overheating**  
  *Fix:* Clean your PC vents/fans, and avoid using it on soft surfaces like beds.

- **Outdated system or drivers**  
  *Fix:* Update Windows and drivers regularly through Settings or Device Manager.

- **Low disk space**  
  *Fix:* Keep at least 10–15% of your disk space free by removing junk files.

- **Fancy visuals**  
  *Fix:* Turn off unnecessary animations and effects in system settings.

- **Heavy apps open**  
  *Fix:* Use one heavy app at a time if your PC is struggling.

- **Broken system files**  
  *Fix:* Run `sfc /scannow` in Command Prompt as admin to fix corrupted files.

- **Unwanted apps**  
  *Fix:* Uninstall apps you never use from Control Panel or Settings.

# DAY 6 : 
# 💻 BSOD (Blue Screen of Death) – Troubleshooting Guide

The **BSOD** is a critical Windows error screen that appears when the system encounters a severe issue, forcing an automatic shutdown to prevent damage. It’s commonly linked to hardware failures, driver conflicts, or corrupted system files.

---

## ⚠️ Common Causes
- Outdated or faulty **device drivers**
- **Corrupt system files** or registry entries
- **Incompatible, failing, or overheating hardware** (RAM, GPU, hard drive)
- Improper **BIOS settings** or overclocking
- **Malware or rootkits** interfering with low-level system functions

---

## 🧠 How to Analyze a BSOD

### 1. 🔍 Identify the Stop Code
Look for the **stop error** name on the BSOD screen (e.g. `CRITICAL_PROCESS_DIED`, `IRQL_NOT_LESS_OR_EQUAL`).

### 2. 🕵️ Use Reliability Monitor
Search for **Reliability Monitor** from the Start menu. Check for warnings or critical events just before the crash.

### 3. 🧾 Analyze Minidump Files
Crash dumps are saved to:  
`C:\Windows\Minidump`

Analyze with tools like:
- [BlueScreenView (NirSoft)](https://www.nirsoft.net/utils/blue_screen_view.html)
- [WinDbg (Microsoft)](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/)
- [WhoCrashed](https://www.resplendence.com/whocrashed)

### 4. 📋 Check the Event Viewer
Run `eventvwr.msc` → Go to **Windows Logs > System** to find events around the time of the crash.

---

## 🧰 How to Fix a BSOD

| 🔢 Step | 🛠️ Action |
|--------|-----------|
| **1** | **Update Drivers** — Use **Device Manager** or OEM tools to update graphics, chipset, and network drivers. |
| **2** | **Uninstall Recent Changes** — Remove any apps or drivers installed shortly before the BSOD began. |
| **3** | **System File Check** — Run `sfc /scannow` from Command Prompt (Admin). |
| **4** | **Check RAM** — Use the **Windows Memory Diagnostic** tool. |
| **5** | **Scan for Malware** — Run a full scan using **Windows Defender** or **Malwarebytes**. |
| **6** | **Reset BIOS/Overclocking** — Revert to default BIOS settings if you've overclocked. |
| **7** | **System Restore** — Roll back to a restore point before the crashes started. |
| **8** | **Update Windows** — Ensure all **Windows Updates** and security patches are installed.


