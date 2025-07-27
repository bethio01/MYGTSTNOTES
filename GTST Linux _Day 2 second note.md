

---

## 🔍 What is Linux?
- Linux is a **kernel**, not a complete OS.
- Acts as a bridge between software and hardware.

## 🧠 What is a Kernel?
- Manages:
  - CPU
  - Memory
  - Devices
- Provides core control under the hood.

## 💬 What is a Shell?
- CLI interpreter between user and kernel.
- Common shells: `sh`, `bash`, `zsh`, `fish`
- Check your shell: `echo $SHELL`

---

## 🕰️ History & Evolution
- **UNIX** → Proprietary, created in 1969
- **GNU Project** → Free tools (e.g., `bash`, `tar`)
- **Linux Kernel** → Made open-source by Linus Torvalds
- ✅ GNU + Linux = Fully free Unix-like OS

---

## 🧮 Operating System Components
- Kernel  
- Software packages  
- Desktop Environment  
- File structure  
- Window Manager  

---

## 🖥️ Desktop Environments (DE)
| DE Name      | Notes                       |
|--------------|-----------------------------|
| MATE         | Lightweight, old-school UI  |
| GNOME        | Modern, animated UI         |
| KDE Plasma   | Highly customizable         |
| XFCE         | Fastest and lowest resource |

---

## 🪟 Window Managers
- Lightweight, keyboard-driven UIs: e.g., i3
- Ideal for low-resource virtual setups

---

## 🧭 Linux Distros (Focus: Ethical Hacking)
| Name        | Base    | DE     | Package Manager | Shell |
|-------------|---------|--------|------------------|--------|
| Kali Linux  | Debian  | XFCE   | `apt`            | `zsh`  |
| Parrot OS   | Debian  | MATE   | `apt`            | `bash` |
| Garuda      | Arch    | KDE    | `pacman`         | `fish` |
| BlackArch   | Arch    | CLI    | `pacman`         | `bash` |

---

## 🛠️ How to Deploy Linux (Choose Your GTST Setup)
### A) Main OS
- ✅ Best performance  
- ❌ No fallback OS  

### B) Dual Boot
- ✅ Access both Linux & Windows  
- ❌ Requires bootloader setup  

### C) Live Boot (USB/DVD)
- ✅ Privacy-focused  
- ❌ Limited system access  

### D) Cloud Terminal
- Web-based practice (e.g. [Webminal](https://www.webminal.org))  
- Great for beginners or remote use  

### E) Virtual Machine
- Type 1: Bare-metal (Proxmox)  
- Type 2: Hosted (VirtualBox)  
- Recommended for GTST lab environments  

### F) WSL2 (Windows Subsystem for Linux)
- Run Linux shell inside Windows  
- Setup via Microsoft Store  

---
---
---

