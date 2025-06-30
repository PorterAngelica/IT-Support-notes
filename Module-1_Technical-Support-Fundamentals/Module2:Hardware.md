# 🧠 Module 2: Computer Hardware

Welcome to the second module of the **Google IT Support Professional Certificate**. These notes cover everything related to the physical components of a computer — also known as hardware.

---

## 💻 Introduction to Computers

Computers are all around us: phones, laptops, desktops, ATMs, smart TVs — they’re all computers at their core.

A **computer** is a device that:

- Takes input  
- Processes data  
- Stores information  
- Provides output  

**Key concepts:**
- **Data** = raw information (text, images, sound)
- **Processing** = transforming data into useful info
- **Storage** = saving data for future use

---

## 🧱 Hardware – The Physical Layer

**Hardware** = physical components you can touch.

### 🔌 Common External Hardware (Peripherals)

| Component | Description |
|----------|-------------|
| Monitor | Displays visual output (GUI, videos, text) |
| Keyboard | Input device to type commands or data |
| Mouse | Pointing device for GUI |
| Webcam | Captures video |
| Speakers | Sound output device |
| Printer | Converts digital documents to paper |

---

## 🔗 Ports and Connectivity

**Ports** = connection interfaces for peripherals.

### 🔌 Common Port Types

| Port | Function |
|------|----------|
| USB | Connects peripherals (keyboard, printer, etc.) |
| HDMI/VGA/DP | Video output |
| Ethernet | Wired network connection |
| Audio Jacks | Sound input/output |
| Power Port | Connects to power source |

---

## 🧩 Internal Components

### 🧠 CPU (Central Processing Unit)

- The "brain" of the computer  
- Executes instructions, performs calculations  
- Measured in **GHz** and **cores/threads**

### 💾 RAM (Random Access Memory)

- Temporary memory for active tasks  
- **Volatile** (data erased when powered off)

| RAM Size | Use Case |
|----------|----------|
| 4 GB | Basic tasks |
| 8 GB | Multitasking |
| 16+ GB | Gaming, editing |

### 💽 Storage (HDD / SSD)

| Type | Pros | Cons |
|------|------|------|
| HDD | Cheaper, large capacity | Slower, mechanical |
| SSD | Faster, silent | More expensive |

### 🧠 Motherboard

- Main circuit board  
- Hosts CPU, RAM, ports, and BIOS

### ⚡ Power Supply Unit (PSU)

- Converts AC to DC power  
- Feeds all components with proper voltage

---

## 🧳 Miniature Computers

- **Laptops** = same components, smaller form
- **Smartphones** = use ARM CPUs, compact storage/RAM

---

## 👨‍🔧 Why Hardware Knowledge Matters

- Troubleshooting hardware issues
- Replacing or upgrading components
- Communicating with users
- Diagnosing problems effectively

> 🛠️ IT Support = technicians or doctors for computers.

---

## ✅ Summary Checklist

| Component | Function | Importance |
|----------|----------|------------|
| CPU | Processes instructions | Core performance |
| RAM | Short-term memory | Multitasking |
| Storage | Long-term memory | Boot time, data access |
| Motherboard | Connects components | Integration |
| PSU | Power delivery | Reliability |
| Ports | Device connections | Communication |
| Peripherals | Interaction tools | User input/output |

---

# 💡 How Computers Understand Us

## 1. From Human to Machine Language

- Humans speak natural language  
- Computers only understand **binary** (1s and 0s)  
- Programs convert human commands into binary

📌 Example: Opening a browser runs code in binary processed by the CPU.

## 2. What Are Programs?

- Instructions stored on the hard drive  
- Loaded into RAM so the CPU can execute them faster

## 3. CPU = The Chef

- Follows step-by-step instructions (recipes)  
- Processes one line at a time

🍞 Example: Making a sandwich (each action = one CPU instruction)

---

## 4. How Data Travels

- Via the **External Data Bus (EDB)**  
- Voltage ON = 1, OFF = 0  
- 8-bit, 16-bit, 32-bit, 64-bit = wire width

## 5. CPU Registers

- Tiny storage units: Register A, B, C  
- Like a chef’s prep tables for calculations

---

## 6. How CPU Gets Data from RAM

- **Memory Controller Chip (MCC)** fetches data  
- **Address Bus** sends memory location  
- MCC retrieves and sends data via EDB

💡 RAM = fridge, MCC = chef’s assistant

## 7. Cache = Ultra-Fast Memory

| Level | Speed | Size |
|-------|-------|------|
| L1 | Fastest | Smallest |
| L2 | Fast | Medium |
| L3 | Slower than L1/L2, but faster than RAM | Largest |

🍽️ Cache = pocket snacks  
🧊 RAM = fridge

## 8. Clock Speed & CPU Cycles

- **Clock wire** = sync mechanism  
- 1 GHz = 1 billion cycles/sec  
- Faster clock = more instructions processed

## 9. Overclocking

- Increasing CPU speed beyond factory specs  
- Used in gaming and performance systems

⚠️ Risks:
- Overheating
- System instability
- Shorter lifespan

---

## 🛠️ Instruction Flow Key Components

| Component | Role |
|----------|------|
| CPU | Executes instructions |
| RAM | Fast temporary memory |
| Hard Drive | Long-term storage |
| MCC | Finds & sends data from RAM |
| EDB | Transfers binary data |
| Address Bus | Sends data locations |
| Cache | Stores frequent instructions |
| Clock | Controls processing speed |

---
#### 🧩 Component Descriptions

- **CPU (Central Processing Unit)**  
  The brain of the computer. It performs calculations, runs programs, and processes instructions. Everything the computer does goes through the CPU.

- **RAM (Random Access Memory)**  
  Temporary, fast memory used to store active processes and data. It allows the CPU to access information quickly but is erased when the computer shuts down.

- **Hard Drive (HDD/SSD)**  
  Permanent storage for the operating system, files, and programs. HDDs use spinning disks, while SSDs are faster with no moving parts.

- **MCC (Memory Controller Chip)**  
  Controls access between the CPU and RAM. It locates the data requested by the CPU and sends it through the EDB.

- **EDB (External Data Bus)**  
  A set of wires that transmits data (as binary) between components inside the computer.

- **Address Bus**  
  Sends the specific location of data in memory. It tells the MCC where to find the requested information, not the data itself.

- **Cache (L1, L2, L3)**  
  Ultra-fast memory closer to the CPU than RAM. Stores frequently used data so the CPU doesn’t need to fetch it from RAM repeatedly.

- **Clock (Clock Wire / Clock Signal)**  
  Regulates the timing of all computer operations. The clock speed (measured in GHz) determines how many instructions per second the CPU can process.
## 🧠 Supplemental: CPU Cache & Overclocking
---

### 🔹 Cache Levels

| Cache | Description |
|-------|-------------|
| L1 | Fastest, used per core |
| L2 | Slower, per core |
| L3 | Shared, largest, faster than RAM |

### ⚡ What Is Overclocking?

- Raising CPU clock speed (e.g. 3.2 → 3.5 GHz)  
- Improves performance in demanding tasks

### 🔧 Variables

- **Base Clock**
- **Multiplier**
- **Core Voltage**

### ⚠️ Overclocking Risks

- Overheating
- Crashes
- Hardware damage

---

## ✅ Steps to Overclock a CPU (Safely)

1. **Check Compatibility** (CPU/motherboard)
2. **Clean System** (dust, proper airflow)
3. **Upgrade Cooling** (liquid or high-performance fans)
4. **Use Benchmarking Tools**
5. **Adjust Multipliers & Test Stability**
6. **Monitor Voltage (don’t exceed 1.4V)**

> ⛑️ If in doubt, buy a CPU that meets your needs instead of overclocking.

---

### 📘 End of Module 2

Understanding hardware is a core foundation for IT support. It enables better diagnostics, smarter upgrades, and clear user communication.

➡️ Next: [Module 3 – Networking Basics](#)
