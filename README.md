## 🛡️ Windows Fundamentals 2

**Room:** [Windows Fundamentals 2 — TryHackMe](https://tryhackme.com/room/windowsfundamentals2x0x)  
**Status:** ✅ Completed  
**Date:** *(29 April 2025)*

### 🎯 Objective
To explore key Windows operating system utilities beyond the basics — focusing on how to access and use advanced tools for troubleshooting, performance monitoring, and system configuration.

---

### 🗝️ Key Concepts
- **MSConfig (System Configuration)** — A tool used for managing startup behaviour, boot options, and services; useful for troubleshooting performance or startup issues.  
- **Task Scheduler** — Allows automation of tasks based on triggers and conditions, often used for system maintenance or running scripts.  
- **Event Viewer** — Displays logs of system events, errors, and warnings; key for diagnosing crashes or issues.  
- **Shared Folders & Sessions** — Shows resources shared on the network and who is connected to them in real time.  
- **Registry Editor (regedit)** — A powerful tool to view and edit the Windows Registry; critical for low-level system configuration.  
- **Command Line Tools** — Includes utilities like `ipconfig`, `hostname`, and `netstat` to gather system and network information.  
- **Performance Monitor** — Tracks detailed performance metrics over time for diagnosing bottlenecks and resource use.  
- **Resource Monitor** — Offers a real-time view of CPU, memory, disk, and network activity in a user-friendly dashboard.  
- **System Information (msinfo32)** — Summarises hardware, drivers, software environment, and system components in one place.

---

### 🛠️ Tools Used
- `msconfig` — for managing startup and diagnostic settings  
- `compmgmt.msc` — central hub for tools like Task Scheduler, Event Viewer, and Disk Management  
- `cmd` — used commands like `ipconfig`, `netstat`, and `hostname`  
- `regedit` — viewed the Windows Registry  
- `resmon` — monitored system performance across CPU, memory, disk, and network  
- `msinfo32` — viewed full system hardware and software environment  

---

### ⚠️ Challenges Faced
- Understanding the roles and depth of utilities like Event Viewer and Registry Editor took time.  
- Navigating so many tools at once was a bit overwhelming, but focusing on one tab or utility at a time helped.  
- Remembering which tools launch from MSConfig versus being directly accessible took a bit of trial and error.

---

### 🧠 What I Learned
- MSConfig is more for troubleshooting than for permanent configuration changes.  
- Tools like Task Scheduler and Event Viewer are vital for system automation and event auditing.  
- The Registry is powerful but dangerous — understanding what not to touch is just as important.  
- Command Prompt, even at a basic level, gives insight into networking and system identity.  
- Resource Monitor is an advanced but highly visual way to assess performance issues.

---

### 🌐 Real-World Application:
> System administrators often use tools like `resmon`, `msinfo32`, and `cmd` to troubleshoot slow systems, diagnose issues remotely, or assess potential misconfigurations. Knowing where to look and how to interpret the data is crucial for maintaining operational security and performance.

---

### 💭 Reflections:
- I enjoyed seeing how interconnected these tools are and how they give different levels of visibility into the system.  
- One key takeaway: **the best troubleshooting starts with knowing where to look** — and Windows gives you plenty of places.
