# 📚 Study Guide: Bits and Bytes of Networking

## 🌐 Introduction
Computers communicate with each other in ways that are surprisingly similar to how humans do.

**Example – Verbal Communication:**
- Two people need to speak the **same language** and be able to **hear each other** to communicate effectively.
- If there is **noise**, one person may ask the other to **repeat themselves**.
- If someone **doesn't fully understand**, they may **ask for clarification**.
- Communication can be **one-to-one** or **one-to-many**.
- Usually involves a **greeting** and a **closing**.

**Key Point:**  
Humans follow rules when they communicate, and **computers must also follow rules** — these are called **protocols**.

---

## 📖 What is a Protocol?
A **protocol** is a **defined set of standards** that computers follow to communicate properly.

### Functions of Protocols:
- Ensure computers can **hear** each other.
- Ensure they **speak the same “language”**.
- Ensure they **repeat messages** if not fully delivered.
- Similar to how humans:
  - Repeat unclear messages.
  - Ask for clarification.
  - Address individuals or groups.

---

## 🖧 What is Computer Networking?
**Computer Networking** is the **full scope of how computers communicate** with each other.

It involves:
- Ensuring computers **can hear each other**.
- Speaking in protocols **other computers understand**.
- **Resending** incomplete or lost messages.

---

## 📚 Network Models
There are several models to describe **layers of communication** in networking.

### TCP/IP Model
1. **Physical Layer**  
   Deals with the physical connection between devices — cables, switches, and the hardware that sends raw bits over a medium.

2. **Data Link Layer**  
   Handles node-to-node data transfer and error detection. Protocols include Ethernet and Wi-Fi.

3. **Network Layer**  
   Responsible for routing packets across networks. The main protocol here is **IP (Internet Protocol)**, which addresses and routes data.

4. **Transport Layer**  
   Provides end-to-end communication control and error handling. Protocols include **TCP (Transmission Control Protocol)** for reliable communication and **UDP (User Datagram Protocol)** for faster, connectionless communication.

5. **Application Layer**  
   Contains protocols and services for end-user applications like HTTP (web), FTP (file transfer), DNS (domain name system), and DHCP (dynamic host configuration).
   
| Layer Name        | Protocols                              | Protocol Data Unit (PDU) | Addressing                  |
|-------------------|--------------------------------------|-------------------------|-----------------------------|
| Physical Layer    | Ethernet (physical aspects), cables, switches | Bits                    | Physical (MAC) addresses (at Data Link layer, but related) |
| Data Link Layer   | Ethernet, Wi-Fi                      | Frames                  | MAC (Media Access Control) addresses |
| Network Layer     | IP (Internet Protocol)               | Packets                 | IP addresses                 |
| Transport Layer   | TCP (Transmission Control Protocol), UDP (User Datagram Protocol) | Segments (TCP), Datagrams (UDP) | Port numbers                 |
| Application Layer | HTTP, FTP, DNS, DHCP                 | Data                    | Uses IP and port addressing  |

> **Note:**  
> These models help explain the **layered nature** of networking, where **each layer depends on the one below it**.

### OSI Model
- **7 layers**.
1. Physical  
2. Data Link  
3. Network  
4. Transport  
5. Session  
6. Presentation  
7. Application  

---

## 🪜 Layered Networking Concept
- Protocols at each layer **carry the ones above them** to get data from point A to point B.
- **Example:**  
  - Protocol to send data from **one end of a cable** to the other is different from the protocol to send it **across the planet**.
  - Both must work together for the Internet or business networks to function.

---

## ⚠️ Common Networking Problems
- Sometimes computers **on the Internet** or **business networks** fail to communicate.
- Often, it’s the job of an **IT support specialist** to troubleshoot and fix these issues.

---

## 📝 Quick Recap
- **Protocols** = rules for communication.
- Networking ensures devices can **hear**, **understand**, and **re-send** messages when needed.
- **TCP/IP (5 layers)** and **OSI (7 layers)** are key reference models.
- IT specialists must know **how layers interact** and how to **troubleshoot problems**.


