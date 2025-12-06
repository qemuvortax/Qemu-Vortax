### 📌 **Select the Windows version you want to install**
> Click on a name to jump directly 👇

🔗 | 🖥️ Supported Windows Versions
---|---
💿 **[Windows XP](#-windows-xp)** |
💿 **[Windows Vista](#-windows-vista)** |
💿 **[Windows 7](#-windows-7)** |
💿 **[Windows 8.1](#-windows-81)** |
💿 **[Windows 10](#-windows-10)** |
💿 **[Windows 11](#-windows-11)** |

---

# 🧩 Windows XP

🖼️ **Screenshot Placeholder**
`https://via.placeholder.com/600x350?text=Windows+XP+Screenshot`

📎 **Download ISO**
```text
https://archive.org/download/windows-xp-all-sp-msdn-iso-files-en-de-ru-tr-x86-x64/en_win_xp_pro_x64_with_sp2_vl_x13-41611.iso
```

### 🌐 Install Supermium Browser
Supermium requires XP SP1+, SS3 enabled, and 2GB RAM minimum.

**Steps:**
1. Open Internet Explorer (or any installed browser)
2. Go to:

```text
http://win32subsystem.live/supermium/legacy/
```
3. Download the correct installer (32/64-bit) and run it
4. Recommended: Install Noto Emoji font + create shortcuts
5. Done! Supermium should now work 🚀


🔑 **Activation Key (during setup)**
```text
VCFQD-V9FX9-46WVH-K3CD4-4J3JM
```

---

# 🪟 Windows Vista

📎 **Download ISO**

https://computernewb.com/isos/windows/Windows%20Vista%20SP2%20x64.iso

🖼️ Screenshot Placeholder  
`https://via.placeholder.com/600x350?text=Windows+Vista`

### 🌐 Install Supermium
Same installation steps as XP.

### 🔓 Activation (Using Microsoft Activation Scripts)
1. Install **PowerShell 2.0**
2. Install **.NET Framework 3.5 SP1**
3. Download MAS Script:

https://raw.githubusercontent.com/massgravel/Microsoft-Activation-Scripts/refs/heads/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd

4. Run script → Choose:

3 → TSForge 1 → Activate Windows

---

# 🪟 Windows 7

📎 **Download ISO**

https://computernewb.com/isos/windows/en_windows_7_ultimate_with_sp1_x64_dvd_u_677332.iso

🖼️ Screenshot Placeholder  
`https://via.placeholder.com/600x350?text=Windows+7`

### 🌐 Install Supermium
Same steps as Vista/Xp. Requires 2GB RAM minimum.

### 🔓 Activation

3 → TSForge 1 → Activate Windows

---

# 🪟 Windows 8.1

📎 **Download ISO**

https://computernewb.com/isos/windows/en_windows_embedded_8_1_industry_enterprise_x64_dvd_2710518.iso

🖼️ Screenshot Placeholder  
`https://via.placeholder.com/600x350?text=Windows+8.1`

### 🌐 Install Supermium
Same procedure as Windows 7.

### 🎨 Optional: Classic Start Menu
Install **Open Shell**:

https://github.com/Open-Shell/Open-Shell-Menu/releases/latest

### 🔓 Activation

3 → TSForge 1 → Activate Windows

---

# 🪟 Windows 10

### 📎 Download Links

| Version | Link |
|--------|------|
| 🔧 **Windows 10 IoT Enterprise LTSC 2021** | `https://computernewb.com/isos/windows/en-us_windows_10_iot_enterprise_ltsc_2021_x64_dvd_257ad90f.iso` |
| 🏠 **Windows 10 22H2 (Stock)** | `https://computernewb.com/isos/windows/Windows%2010%2022H2.iso` |

🖼️ Screenshot Placeholder  
`https://via.placeholder.com/600x350?text=Windows+10`

### 🌐 Browser
Edge is pre-installed. You can download Chrome from it.

### 🔓 Activation

3 → TSForge 1 → Activate Windows

---

# 🪟 Windows 11

### 📎 Download Links

| Version | Link |
|---------|------|
| 🔧 **Windows 11 IoT Enterprise LTSC 2024** | `https://computernewb.com/isos/windows/en-us_windows_11_iot_enterprise_ltsc_2024_x64_dvd_f6b14814.iso` |
| 🏠 **Windows 11 24H2 (Stock)** | `https://computernewb.com/isos/windows/Windows%2011%2024H2.iso` |

🖼️ Screenshot Placeholder  
`https://via.placeholder.com/600x350?text=Windows+11`

### 🔧 Bypass Secure Boot / TPM / CPU / RAM Requirements
> **Only required for the Stock version**

1. When you reach the language selection screen, press:

Shift + F10

2. Execute the following commands **one by one**:

reg add HKLM\SYSTEM\Setup\LabConfig



reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassTPMCheck /d 1



reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassSecureBootCheck /d 1



reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassRAMCheck /d 1



reg add HKLM\SYSTEM\Setup\LabConfig /t REG_DWORD /v BypassCPUCheck /d 1

### 🌐 Browser
Edge is pre-installed. Chrome can be downloaded normally.

### 🔓 Activation

3 → TSForge 1 → Activate Windows

---