# Introduction to Operating Systems

A lot of people hear the term **operating system** and think of the interfaces on their desktops or phones — the menus, buttons, and backgrounds. Technically, these are part of the operating system, but the concept goes much deeper.

An **operating system** is the complete package that manages a computer’s resources and allows users to interact with it.

---

## 🔧 The Two Main Components of an Operating System

There are two core components of every operating system:

### 1. **The Kernel**
- The **kernel** is the heart of the operating system.
- It communicates directly with the hardware.
- Manages system resources (CPU, memory, I/O).
- Users do **not** interact with the kernel directly.

### 2. **User Space**
- Everything **outside** the kernel.
- This includes:
  - System programs
  - User interfaces
  - Applications we interact with

When we refer to an operating system, we mean both the **kernel** and the **user space**.

---

## 💻 Major Operating Systems in IT

There are hundreds of operating systems, but in IT support, we focus on the following major ones:

### 🪟 Windows OS
- Developed by **Microsoft**
- Widely used in both business and consumer environments
- Most pre-built PCs come with Windows by default
- While "PC" means "Personal Computer," in modern use it's often synonymous with a Windows computer

### 🍎 macOS
- Developed by **Apple**
- Mostly used in the consumer space
- Pre-installed on Apple computers

### 🐧 Linux
- **Open-source** operating system
- Free to share, modify, and distribute
- Widely used in:
  - Business infrastructure
  - Consumer devices
- **Linux** is actually a **kernel**, originally developed by **Linus Torvalds**
- Now a massive community-driven effort

#### Linux Distributions
Because Linux is open-source, many organizations build their own versions, called **distributions (distros)**:
- Common distros: **Ubuntu**, **Debian**, **Red Hat**

---

## 📱 Other Operating Systems

- **Chrome OS** (not covered in depth here) is gaining popularity
- **Mobile OS usage** exceeds desktop usage worldwide
- Fun fact: **Chrome OS** and **Android OS** both run the **Linux kernel** underneath

---

## 🔍 Why Learn This?

Understanding the building blocks of **one OS** makes it easier to understand **any OS**.

In IT support, you’ll often work with:
- Desktop OSs
- Mobile OSs
- And more...

---

## 🧠 Core Functions of the Kernel

Let’s break down the four major functions the kernel performs:

### 1. **File Management**
- Manages file storage and retrieval
- Comparable to an office file system with folders and cabinets
- Data is stored as files: documents, pictures, music, etc.
- Files are organized using **directories (folders)** to avoid chaos
- Different operating systems use different **file systems** (we’ll explore this in detail later)

### 2. **Process Management**
- Manages execution of multiple programs (processes)
- Controls:
  - Order of execution
  - Resource allocation
  - Runtime duration
- Includes a **process scheduler** that allows multitasking by rapidly switching between processes
- Gives the **illusion of simultaneous actions**

### 3. **Memory Management**
- Optimizes system memory usage
- Ensures applications have enough memory to function
- Prevents memory conflicts between processes

### 4. **Input/Output (I/O) Management**
- Manages communication with external devices:
  - Disks
  - Keyboards
  - Mice
  - Network connections
  - Audio devices
- If you've ever:
  - Saved a file
  - Clicked a mouse
  - Used a microphone during a video call  
  You’ve experienced I/O management in action

---

## 👤 What Is the User Space?

The **user space** is the layer we interact with directly, and includes:
- Programs (e.g. text editors, media players)
- User interfaces (e.g. desktop environments)
- System settings and controls

---

## ✅ Summary

By now, you should have a basic understanding of:

- What an operating system is
- The two core components: **Kernel** and **User Space**
- Major operating systems in IT
- The kernel’s core functions:
  - File Management
  - Process Management
  - Memory Management
  - I/O Management

---

