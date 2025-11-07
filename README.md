
# Qemu-Vortax V1.0

Run any operating system (ISO, QCOW2, or compressed archives) directly on GitHub Actions with full graphical access via **XFCE, RDP, VNC, NoMachine, and Tailscale**.

---

## ⚙️ Overview

**Qemu-Vortax** is an educational and experimental GitHub Actions workflow that allows you to boot and interact with virtual machines in a full graphical desktop environment—right inside the GitHub cloud.  
You can run Linux distributions, Windows builds, or custom disk images using ISO or QCOW2 formats.

> 🧠 Educational use only.  
> The author is **not responsible** for any banned accounts, data loss, or issues that may result from misuse.  
> Use this workflow **at your own risk**.

---

## 🚀 Features

- 🧩 **Multi-OS boot support**: Run any `.iso`, `.qcow2`, or compressed archive (`.zip`, `.7z`, `.rar`, `.tar`, `.tar.gz`).
- 💻 **Full GUI desktop (XFCE)** over RDP, VNC, and NoMachine.
- 🛰️ **Secure networking via Tailscale** (your personal encrypted tunnel).
- 📦 **Auto-decompression** for supported archive formats.
- 🔁 **Multiple ready-to-use systems** (see below).
- 🧰 **Dynamic boot type detection** – auto-handles ISO or QCOW2.
- ⏱️ **Session timer** to control VM runtime.
- 🧠 **Custom download sources** (MediaFire, Mega, direct links, etc.).
- 🔒 **Isolated environment** – each run is sandboxed within GitHub Actions.
- 🌐 **Cross-access from any device** – just copy the RDP/VNC/Tailscale link.
- 💾 **Persistent storage simulation** (via temporary QCOW2 disks).
- ⚡ **Fast launch** – VM boots in minutes.

---

## 🛠️ How to Use

### 1. Fork this Repository

Click **Fork** on the top-right corner of this repo.

### 2. Set the Tailscale Auth Key

- Go to **Repository Settings → Secrets → Actions → New repository secret**.
- Name it: `TAILSCALE_AUTHKEY`
- Paste your Tailscale auth key value.

### 3. Run the Workflow

1. Open the **Actions** tab.  
2. Select **Qemu-Vortax V1.0**.  
3. Click **Run workflow** and fill the following inputs:

---

## 🧾 Workflow Inputs

| Input | Description | Example |
|-------|--------------|----------|
| `system_choice` | Choose one of the pre-set OS options (see list below) | `ubuntu`, `mint`, `kali`, `deepin` |
| `boot_mode` | Define boot type (`iso` or `qcow2`) | `iso` |
| `source_url` | Custom link (ISO/QCOW2/Archive/MediaFire/Mega) | `https://example.com/myos.iso` |
| `vm_name` | Custom name for your VM session | `my-linux` |
| `runtime` | Session duration in minutes (after setup time) | `180` |

> ⚠️ Important:
> - When using custom links, make sure there are **no spaces** before or after any input.  
> - Always match the **boot mode** with your file type (ISO/QCOW2).  
> - For compressed archives, specify the correct type (ZIP, 7Z, RAR, TAR, TAR.GZ).

---

## 🧩 Pre-set Systems

| System | Boot Type | Description | Screenshot |
|--------|------------|--------------|-------------|
| `ubuntu` | ISO | Classic Ubuntu desktop with XFCE, stable and lightweight. | ![Ubuntu](assets/ubuntu.png) |
| `mint` | ISO | Linux Mint XFCE edition for smooth and modern experience. | ![Mint](assets/mint.png) |
| `kali` | ISO | Kali Linux for penetration testing and ethical hacking labs. | ![Kali](assets/kali.png) |
| `pear` | ISO | Pear Linux, macOS-style Ubuntu derivative focused on elegance and simplicity. | ![Pear](assets/pear.png) |
| `deepin` | ISO | Deepin Linux with an elegant UI and strong customization. | ![Deepin](assets/deepin.png) |
| `popos` | ISO | Pop!_OS optimized for developers and creators. | ![PopOS](assets/popos.png) |
| `bazite` | ISO | Minimal distro focused on performance and clean design. | ![Bazite](assets/bazite.png) |
| `neon` | ISO | KDE Neon with the latest Plasma environment. | ![Neon](assets/neon.png) |
| `bliss_gapps` | ISO | Android-based OS with Google Apps pre-installed. | ![BlissGapps](assets/bliss_gapps.png) |
| `garuda_mokka` | ISO | Garuda Linux Mokka edition for gaming and speed. | ![Garuda](assets/garuda.png) |
| `manjaro` | ISO | Manjaro GNOME 25.0.10, a fast and user-friendly Arch-based distribution. | ![Manjaro](assets/manjaro.png) |
| `cutefish` | ISO | CutefishOS 22.04, Ubuntu-based system with a clean macOS-like interface. | ![Cutefish](assets/cutefish.png) |
| `debian_qcow2` | QCOW2 | Debian 12 Bookworm cloud image preconfigured for QEMU. | ![Debian](assets/debian_qcow2.png) |
| `centos_qcow2` | QCOW2 | CentOS Stream 10 GenericCloud image for stable enterprise environments. | ![CentOS](assets/centos_qcow2.png) |
| `kali_qcow2` | QCOW2 | Kali Linux 2025.3 QEMU-ready build for penetration testing. | ![Kali](assets/kali.png) |
---

## 🖥️ Connection Options

After the VM starts, you’ll see connection details printed in the log:

| Type | Address format | Use |
|------|----------------|-----|
| **RDP** | `ip:3389` | Connect via Remote Desktop (Windows/macOS/Linux). |
| **VNC** | `ip:5900` | Use VNC Viewer or Remmina. |
| **NoMachine** | auto-configured | High-speed remote access. |
| **Tailscale** | secure tunnel | Access VM from any device privately. |

---

## ⚡ Performance Tips

- Increase `runtime` for longer sessions.
- Use `qcow2` format for faster boot after first run.
- Use compressed archives only when needed (they add decompression time).
- Always check file integrity before using a custom link.

---

Licensed under the **MIT License**.  
You can use, modify, and redistribute this workflow freely, but attribution is appreciated.

---

## ⚠️ Disclaimer

This project is provided for **educational and experimental use only**.  
By running this workflow, you acknowledge that:
- You are responsible for any actions performed.
- The author is **not liable** for bans, account issues, or data loss.
- Use it **at your own risk**.

---

## 🧠 Credits

Developed by **Mohamed Ahmed Saad**  
Project: **Qemu-Vortax V1.0**  
Inspired by the goal of making virtual machine testing easier and faster in the cloud.

---


---
