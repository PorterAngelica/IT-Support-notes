# 🌐 The Web – Study Guide

The web is one of the most popular ways people interact with the internet. In this guide, you'll learn what it is, how it works, and how it connects with concepts like URLs, domain names, IP addresses, and DNS.

---

## 📖 What Is the Web?

The **web** (short for World Wide Web) is a system of interlinked documents and other media that can be accessed via the internet using a web browser.

Websites on the web are essentially **text documents** written using **HTML (HyperText Markup Language)**.

### Common features of a webpage:
- **Text**
- **Images**
- **Audio**
- **Video**

These documents are hosted on web servers and delivered to your browser when you request them using a URL.

---

## 🔗 URLs – Uniform Resource Locators

A **URL** is the address of a webpage. It tells your browser where to go to retrieve content.

### Example:https://www.reddit.com


### Parts of a URL:
1. **`https://`** – The protocol used (HTTPS in this case).
2. **`www`** – Stands for *World Wide Web*.
3. **`reddit.com`** – The **domain name**.

> 🔍 **Analogy**: A URL is like a full address for a house. If the internet were a city, the URL tells your browser how to find the specific building (site) and room (page).

---

## 🏠 Domain Names

A **domain name** is the human-friendly name of a website, such as:
- `google.com`
- `reddit.com`
- `harvard.edu`

Domains are registered through a central authority called **ICANN** (Internet Corporation for Assigned Names and Numbers).

> Once a domain is registered, no one else can use it — unless it expires.

### Common domain endings:
- `.com` → Commercial
- `.org` → Organization
- `.net` → Network infrastructure
- `.edu` → Educational institutions
- `.gov` → Government

---

## 🌍 IP Addresses and the Web

Computers don’t understand domain names. They need **IP addresses** to find each other.

Example:  
Typing `172.217.6.46` into your browser might take you directly to **Google’s homepage**.

> ✅ Behind the scenes, every domain name is linked to an IP address.

This translation is done through something called **DNS**.

---

## 📖 DNS – Domain Name System

**DNS (Domain Name System)** is like the **phonebook** or **directory** of the internet.  
It converts human-readable domain names like `google.com` into IP addresses like `172.217.6.46`.

### Why DNS matters:
- Without DNS, you'd have to memorize IP addresses.
- Every time you visit a website, your browser does a **DNS lookup**.

### Example scenario:
If `google.com` isn’t working but `172.217.6.46` works, then the problem might be a **DNS configuration issue**.

> 🔧 IT Tip: Diagnosing DNS is a common step in troubleshooting internet connectivity problems.

---

## 🧠 Why This Matters in IT

Understanding how the web works and how DNS functions is critical for IT professionals because:
- DNS issues are common and need troubleshooting.
- Server logs identify users by IP addresses.
- Devices must be configured with valid IP addresses to access the internet.
- Web traffic analysis and cybersecurity depend on knowledge of IP/DNS systems.

---

## 🗂 Glossary of Key Terms

| Term              | Definition |
|-------------------|------------|
| **Web (World Wide Web)** | A system of interlinked documents accessed via browsers on the internet. |
| **HTML (HyperText Markup Language)** | The standard language used to create web pages. |
| **URL (Uniform Resource Locator)** | The address used to access a specific resource on the web. |
| **Domain Name**   | The human-readable name for a website (e.g., google.com). |
| **ICANN**         | Internet Corporation for Assigned Names and Numbers – manages domain name registration. |
| **IP Address**    | A numeric identifier for a device on a network (e.g., 172.217.6.46). |
| **DNS (Domain Name System)** | Translates domain names to IP addresses. |
| **DNS Lookup**    | The process your computer uses to find the IP address behind a domain name. |
| **Protocol**      | A set of rules for data transfer over the network (e.g., HTTP, HTTPS). |

---

## ✅ Next Steps

To go deeper:
- Learn how **DNS records** work (A, CNAME, MX, etc.).
- Explore **HTTP and HTTPS protocols**.
- Try using `nslookup` or `dig` commands to see DNS queries in action.
- Understand how browsers cache DNS responses.

---

This marks the end of your introduction to **The Web**. Up next: the internet boom and how it changed everything.

