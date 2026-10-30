# Jesús Alejandro Cortés (`knju`)

**Linux Systems Administrator | Infrastructure & Automation | Support & Security Engineering**  
📍 Santa Cruz de Tenerife, Spain (EU • Remote-Ready) • 🌐 [**knju.dev**](https://knju.dev) • 📫 [jcor.alejandro@gmail.com](mailto:jcor.alejandro@gmail.com)

---

### `$ whoami`

Hands-on Linux systems administrator and infrastructure builder focused on self-hosted production environments, rootless container architectures, network protocol analysis, and systems automation. 

- **Daily Driver & Lab:** Arch Linux (`linux-zen` / Hyprland / QuickShell) on the desktop; hardened Debian, rootless Podman, and QEMU/KVM + OPNsense on the server and virtualized network stack.
- **Automation First:** If a workflow has to be done twice, I script it in **Python**, **Bash**, or **Fish**, or wire it directly into system IPC sockets and systemd units.
- **Languages:** Native/Bilingual **English** & **Spanish**.

---

### Featured Infrastructure & Engineering Work

#### 1. Self-Hosted Container-to-Host CI/CD Pipeline ([`knju.dev`](https://knju.dev))
Designed and deployed an end-to-end automated publishing infrastructure from scratch on a hardened Debian node:
- **Isolated Git Hosting:** Self-hosted **Forgejo** instance running inside **rootless Podman** (port `2222`) fronted by an **Nginx** reverse proxy.
- **Cross-Boundary Webhook Engine:** Custom **Python HTTP webhook listener** on the host OS bound across the container bridge (`10.89.0.1`) with strict **SSRF mitigations** and payload validation.
- **Zero-Downtime Releases:** Automated **Bash** build pipeline triggered on `git push` to pull commits, compile static assets via **Hugo**, and atomically update production web roots.

#### 2. Offensive Security Tooling & Real-Time Lab Telemetry
Custom tooling built for penetration testing labs (Hack The Box) and protocol reverse-engineering:
- **Protocol Exploitation (`attack.py`):** Custom Python raw-socket exploit built to reverse-engineer and compromise a non-standard Line Printer Daemon (LPD) network service (*HTB Paperwork*) where standard enumeration tools failed.
- **Wayland VPN/Target Telemetry (`htb-watch` & `HtbStatus.qml`):** Background shell daemon, Fish workflow functions (`target`), and a native **QuickShell/QML** status module that parses active `tun0` VPN interfaces and renders live target IP/box telemetry directly on the desktop HUD.

#### 3. Remote Wayland IPC Controller
- Lightweight **Python HTTP server** and responsive web control surface that interfaces directly with **Hyprland IPC sockets** (`hyprctl dispatch`) to execute low-latency window management and system macros remotely over the LAN.

#### 4. Linux Onboarding & Technical Documentation Series (ES)
- Authored a three-part Spanish technical guide series—***Introducción a Linux***, ***Iniciación a Linux***, and ***Inmersión en Linux***—designed to take vocational IT students from foundational CLI navigation and permissions to practical system administration.

---

### Technical Stack

| Domain | Technologies & Tooling |
| :--- | :--- |
| **Operating Systems** | ![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white) ![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white) ![Windows](https://img.shields.io/badge/Windows_10%2F11-0078D6?style=flat-square&logo=windows&logoColor=white) `systemd` • `Btrfs` • `PipeWire` • `BIOS/UEFI & ACPI Tuning` |
| **Containers & Virt** | ![Podman](https://img.shields.io/badge/Rootless_Podman-892CA0?style=flat-square&logo=podman&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![QEMU](https://img.shields.io/badge/QEMU%2FKVM-FF6600?style=flat-square&logo=qemu&logoColor=white) `libvirt` • `Infrastructure as Code (IaC)` |
| **Networking & Sec** | ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![WireGuard](https://img.shields.io/badge/WireGuard%2FOpenVPN-88171A?style=flat-square&logo=wireguard&logoColor=white) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) `OPNsense` • `TCP/IP • DNS • DHCP • VLANs` • `Hack The Box` |
| **Scripting & Dev** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash%2FFish-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) ![Git](https://img.shields.io/badge/Git%2FForgejo-F05032?style=flat-square&logo=git&logoColor=white) ![Hugo](https://img.shields.io/badge/Hugo-FF4088?style=flat-square&logo=hugo&logoColor=white) `QML (QuickShell)` • `Lua` • `HTML/CSS/JS` |

---

### Current Focus
- **Formal Training:** *Técnico Superior en Administración de Sistemas Informáticos en Red (ASIR)* & Cisco CCNA routing/switching labs.
- **Homelab & Security:** Expanding automated infrastructure deployment playbooks, hardening containerized services, and breaking machines on Hack The Box.
