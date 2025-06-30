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

🔁 Redirection in Linux
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

---

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



### FILE COMPRESSION :
### WILDCARD AND ESCAPING CHARACTERS :


