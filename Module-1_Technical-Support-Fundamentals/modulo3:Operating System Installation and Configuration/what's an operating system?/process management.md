# ⚙️ Process Management

One of the most important tasks that the **kernel** performs is **process management**.

---

## 🧠 What Is a Process?

- A **process** is an instance of a **program** that is currently executing.
  - Example: Your internet browser or text editor while running.
- A **program** is simply an application that can be launched — like Chrome.
- You can have **many processes** from the **same program** running at the same time.
  - Example: Multiple Chrome windows = multiple processes of the Chrome program.

---

## 🔄 Resource Allocation

To run programs, the computer needs to dedicate resources like:

- **RAM** (Memory)
- **CPU** (Processing Power)

Since these resources are limited, the kernel ensures efficient distribution so that multiple programs can operate simultaneously.

---

## 🏃‍♂️ System Processes

The system is **always** running many processes in the background — not just the ones the user launches.  
The kernel must constantly manage **all** of these to keep the system functioning properly.

---

## 🔁 Process Creation

When a program is executed:
1. A **process is created**.
2. The process requires **hardware resources** (CPU & RAM).
3. The **kernel schedules CPU time** to execute instructions in the process.

---

## ⏱️ Time Slicing

Since there is usually only **one CPU**, how does it handle multiple processes?

- The kernel uses **time slicing**:
  - A **time slice** is a **tiny interval** of CPU time allocated to a process.
  - The CPU executes one process for a few **milliseconds**, then switches to the next.
  - This creates the **illusion of simultaneous execution**, but it’s actually **rapid switching**.

Example:

```plaintext
Process A → [time slice]
Process B → [time slice]
Process C → [time slice]
...repeat...

