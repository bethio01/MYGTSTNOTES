
# # 🐧 Introduction to Linux – Day 2 Notes

## 📚 Last Class Topics
- [Recap not specified]

## 📌 Today’s Agenda
- What is Linux?
- What is a kernel?
- History of Linux
- What is a shell and its types
- What is an OS?
- Linux distributions (Distros)

---

## 🌱 What is Linux?
- Linux is a **kernel**, not a complete operating system.
- It bridges software and hardware and allocates resources like CPU, memory, and devices.

---

## 🧠 Kernel
- A program that manages interaction between applications and hardware.
- Core component of any OS:
  - Handles memory, processes, device control, etc.

---

## 🕰️ History of Linux
- UNIX (1969) by Ken Thompson and Dennis Ritchie—proprietary and not open-source.
- GNU Project (1983) by Richard Stallman—created free software tools.
- **Linux kernel** (1991) by Linus Torvalds—developed in C and made open-source.
- **GNU/Linux = Linux kernel + GNU tools**

---

## 💬 Shell: Command Line Interpreter
- Lets users interact with the kernel.
- Popular shells:
  - `sh`
  - `bash`
  - `zsh`
  - `fish`
- To identify your shell: `echo $SHELL`

---

## 🧮 What is an Operating System?
- Software that allows users to interact with hardware.
- Components:
  - Kernel
  - Desktop Environment
  - Package Manager
  - Window Manager
  - User-space applications

---

## 🖼️ Desktop Environments
Visual interfaces for user interaction.

| Environment | Features |
|-------------|----------|
| **MATE**    | Lightweight, traditional UI |
| **GNOME**   | Modern, animations, user-friendly |
| **KDE Plasma** | Highly customizable, rich features |
| **XFCE**    | Lightweight, fast, low resource usage |

---

## 🪟 Window Managers
- Examples: i3, Openbox
- Manage window placement and layout independently of desktop environments.

---

## 🚀 Why Linux?
- Lightweight and fast
- Secure and open-source
- Dominates servers, supercomputers, smartphones
- Supports hacking, development, and research tools
- Used by 47% of professional developers

---

## 📦 Linux Distributions (Distros)
Distros = Linux kernel + GNU packages + desktop environments + package managers.

### Beginner-Friendly
- Ubuntu
- Linux Mint
- MX Linux
- Zorin OS

### Intermediate
- Fedora
- Pop!_OS
- Manjaro
- Elementary OS

### Advanced / DIY
- Arch
- Gentoo
- Linux From Scratch

### Hacking-Focused
- Kali Linux (Debian-based, XFCE)
- Parrot OS (Debian-based, MATE)
- Garuda Linux (Arch-based, KDE Plasma)
- BlackArch (Arch-based)

---

## 🛠️ How to Use Linux
### A) Main OS Install
- ✅ High performance
- ❌ Risk of data loss

### B) Dual-Boot
- ✅ Access to Windows + Linux
- ❌ Complex setup

### C) Live Boot (from USB/DVD)
- ✅ Privacy, no install needed
- ❌ Limited performance and resource sharing

### D) Cloud Terminals
- Example: Webminal.org
- ✅ Accessible from browser
- ❌ Requires internet access

### E) Virtual Machine
- Type 1 (Bare Metal): Runs directly on hardware (Proxmox, ESXi)
- Type 2 (Hosted): Runs atop an OS (VirtualBox, VMware Workstation)

### F) WSL (Windows Subsystem for Linux)
- Run Linux terminals inside Windows
- Install distros from Microsoft Store

### G) Termux (on Android)
- Lightweight Linux environment for scripting and learning

---
---
---
