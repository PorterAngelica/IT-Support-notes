# Installing Linux 🐧

---

## Introduction  
Now that we've seen how Windows is installed, let's go ahead and install the Linux operating system. Linux comes in many different versions called **distributions**. There are hundreds of them with various pros and cons, but we'll use the most popular consumer distribution: **Ubuntu**.

---

## Preparing the USB Drive  
I've already loaded Ubuntu on a plain USB drive.

> **Pro tip:**  
> Since Ubuntu is open source, you can download the free OS image directly from their website and install it using any bootable media you like.  
>  
> **Important:** You *can’t just copy* the install file to a USB drive. The USB needs to be made bootable from the BIOS. Use a tool like [Etcher](https://www.balena.io/etcher/) to create a bootable USB.  

When ready, power on your PC and make sure to set it to boot from the USB device.

---

## Starting the Installation  
Once Ubuntu loads, you'll get two options:

- **Try Ubuntu first** (runs it live without installing)  
- **Install Ubuntu** (fresh install)

We will choose **Install Ubuntu** for a clean setup.  

You'll see the Ubuntu logo and some loading screens while the system prepares for installation. For now, just accept the defaults.

---

## Setup Details  
You'll be asked for:

- **Your name**  
- **Computer name / Hostname** — used to identify the computer on a network  
- **Username** — your login name  
- **Password** — to secure your account  

Example:  
**Name:** Cindy  
**Hostname:** Cindy-NYC (industry standard: username-location)  

After filling in the details, click **Next**. The system will install and prompt you to restart when finished.

---

## Logging In  
After restart, log in using the username and password you created.

---

## Ubuntu Desktop Overview  
Welcome to the Ubuntu desktop environment! Here's what you see:

- **Left-side Dock:** shortcuts to frequently used apps  
- **Top-right bar:** quick settings for network, Bluetooth, sound, time, power options  

Click the menu and select **System Settings** to adjust things like:

- Screensaver  
- Screen resolution  
- Hardware settings  

---

## File Management  
Back on the desktop, click the **Files** icon to open the file manager. Here you can browse your files and folders.

Clicking **Computer** takes you to the system's root directory (advanced topic for later).

---

## Creating a File Using the Terminal  

1. Open the **Terminal** app (search for "Terminal").  
2. You'll see a command prompt like this:  
   ```bash
   username@hostname:~/Desktop$
This shows the current user, hostname, and directory (Desktop).  
3. To check your shell, type:

    echo $SHELL

It should return:

    /bin/bash

(This means you are using the Bash shell.)  
4. To create a file, use the touch command:

    touch "my super cool file"

This creates a new empty file on your Desktop.  

Why Learn Commands?  
You might wonder:  
Why memorizing Linux shell commands is necessary when using a GUI is easier?  

Answer:  
If you work with Linux machines (especially remotely), knowing commands is essential.  
The terminal offers powerful control that a GUI can’t always provide.  

Resources  
Ubuntu Official Download  
Etcher: Create Bootable USB  

That's it! You now have a fresh Ubuntu Linux installation and the basics to get started using the terminal! 🎉
---

# 🐧 How to Install Linux (Ubuntu) on Your Computer — Step-by-Step Guide

### 🧰 Requirements
- A computer where you want to install Linux  
- A USB flash drive (at least 4 GB)  
- Another working computer to create the bootable USB (if needed)  
- Ubuntu ISO file (free download from the official site)  
- Etcher software (or similar) to create the bootable USB  
- Patience and attention to detail!

---

### 🔗 Download Ubuntu ISO and Etcher
- Download Ubuntu here: https://ubuntu.com/download/desktop  
- Download Etcher here: https://www.balena.io/etcher/

---

### 🔥 Step 1: Create a Bootable USB Drive
1. Insert your USB drive into a working computer.  
2. Open Etcher.  
3. Select the Ubuntu ISO file you downloaded.  
4. Select your USB drive as the target device.  
5. Click “Flash” or “Start” to create the bootable USB.  
6. **Important:** This will erase everything on your USB, so back up any files you want to keep.

---

### 💻 Step 2: Boot Your Computer from USB
1. Insert the USB into the computer where you want to install Linux.  
2. Turn off the computer completely.  
3. Turn it back on and immediately press the boot menu key (varies by brand):  
   - Dell: F12  
   - HP: Esc or F9  
   - Lenovo: F12  
   - ASUS: F8 or Esc  
   - Acer: F12  
4. From the boot menu, select your USB drive.

---

### 🧭 Step 3: Try or Install Ubuntu
1. When Ubuntu boots, you'll see two options:  
   - **Try Ubuntu** (runs Linux without installing)  
   - **Install Ubuntu** (fresh installation)  
2. Select **Install Ubuntu**.

---

### ⚙️ Step 4: Go Through Installation Setup
1. Select your language and click **Continue**.  
2. Choose keyboard layout and click **Continue**.  
3. Connect to Wi-Fi if prompted.  
4. Choose installation type:  
   - Select **Erase disk and install Ubuntu** if you want a fresh install (this deletes everything on the disk).  
   - Or choose **Something else** if you want to manually manage partitions (advanced users).  
5. Click **Install Now** and confirm.

---

### 📝 Step 5: Configure User Info
1. Enter your name.  
2. Enter a computer name (hostname). For example, "yourname-PC".  
3. Choose a username and a strong password.  
4. Click **Continue**.  

---

### ⏳ Step 6: Wait for Installation to Finish
- The installer will copy files and configure your system.  
- When done, it will ask you to restart. Remove the USB and press Enter.

---

### 🎉 Step 7: Log into Your New Ubuntu System
- After reboot, log in with your username and password.  
- You’ll see the Ubuntu desktop environment.  

---

### 🧑‍💻 Step 8: Explore and Get Familiar
- On the left side, there’s a dock with your apps.  
- Top right corner has settings for Wi-Fi, sound, and power options.  
- Open **Settings** to customize your system (display, users, updates, etc).  
- Try opening the **Terminal** to start learning Linux commands!  

---

### 💡 Tips for Beginners
- Linux might seem different at first, but you’ll get used to it quickly.  
- Use the terminal for powerful control (learn basic commands like `ls`, `cd`, `touch`).  
- Keep your system updated via the Software Updater.  
- Explore free software available for Linux for productivity, media, and development.

---
# 🖥️ Beginner's Guide to Basic Linux Terminal Commands

When you install Ubuntu or any Linux distro, learning terminal commands is essential to get the most out of your system. Here are some foundational commands explained step-by-step:

1. **Open the Terminal**  
- Press `Ctrl + Alt + T`  
- Or search for **Terminal** in your app menu  

2. **Check Current Directory**  
`pwd` means “print working directory” and shows the folder you are currently “in”. Use the command:  
`pwd`

3. **List Files and Folders**  
Lists all files and directories in the current folder with:  
`ls`  
Use `ls -l` for detailed info (permissions, size, date)  
Use `ls -a` to show hidden files (those starting with a dot)  

4. **Change Directory**  
Moves you into the folder named `foldername`:  
`cd foldername`  
Use `cd ..` to move up one level  
Use `cd` alone to go to your home directory  

5. **Create a New File**  
Creates an empty file named `filename.txt`:  
`touch filename.txt`  
You can then edit it with text editors like nano or gedit  

6. **Create a New Directory (Folder)**  
Creates a new folder named `myfolder`:  
`mkdir myfolder`  

7. **Delete a File**  
Deletes the file named `filename.txt` (be careful, this is permanent!):  
`rm filename.txt`  

8. **Delete a Directory and Its Contents**  
Deletes `myfolder` and everything inside it recursively:  
`rm -r myfolder`  

9. **Copy Files or Directories**  
Copies `source.txt` to `destination.txt`:  
`cp source.txt destination.txt`  
Use `cp -r myfolder newfolder` to copy folders recursively  

10. **Move or Rename Files and Directories**  
Moves or renames `oldname.txt` to `newname.txt`:  
`mv oldname.txt newname.txt`  

11. **View File Contents**  
Displays the contents of `filename.txt` in the terminal:  
`cat filename.txt`  

12. **Get Help on Commands**  
Opens the manual page for a command, for example `ls`:  
`man ls`  
Press `q` to quit the manual  

---

### Why Learn These Commands?

- **Power:** Terminal commands let you do tasks faster and automate things.  
- **Remote Access:** Many servers and Linux machines are managed remotely via SSH terminal.  
- **Flexibility:** You can combine commands to perform complex tasks easily.  

---

### Example Session

- pwd
- ls
- mkdir testfolder
- cd testfolder
- touch testfile.txt
- ls
- cat testfile.txt
- cd ..
- rm -r testfolder



