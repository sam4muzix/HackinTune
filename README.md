<p align="center">
  <img src="masked_icon.png" width="200" alt="HackinTune Logo">
</p>

# 🍏 HackinTune: The Mighty Hackintosh Companion
**Smart Hardware Repair • Ultimate Performance**

[![Latest Release](https://img.shields.io/github/v/release/sam4muzix/HackinTune?color=brightgreen&label=Latest%20Release)](https://github.com/sam4muzix/HackinTune/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: macOS](https://img.shields.io/badge/Platform-macOS-blue.svg)](https://www.apple.com/macos/)

**HackinTune** is a premium macOS native utility designed to simplify and supercharge the entire Hackintosh journey—from generating solid EFI builders to managing smart repairs on a running system.

---

## ⚡ Key Features

### 🛠️ Pre-Install: EFI Builder & Setup
*   **Smart EFI Builder**: Dynamically generates solid OpenCore EFI folders based on your hardware selections and CPU generation (Intel 10th to 14th Gen).
*   **Solid Configurations**: Tailored SSDTs (e.g., `SSDT-PLUG-ALT` for 12th+ Gen) and pre-configured drivers for a "perfect first boot."
*   **macOS Installer Creator**: Directly fetches official macOS versions from Apple's servers and creates bootable USB media with real-time logs.

### 🔧 Post-Install: Smart Hardware Repair
*   **Intelligent System Scan**: Real-time identification of Internal (PCI) and External (USB) Wi-Fi, Bluetooth, and Audio hardware.
*   **Safety Compatibility Guard**: Advanced logic that matches drivers to specific Vendor IDs (Intel, Broadcom, Realtek). Incompatible injections are blocked to prevent system crashes.
*   **USB Device Detection**: Specialized support for external Wi-Fi dongles and Bluetooth adapters with direct links to recommended driver repositories.
*   **One-Click Optimization**: 
    *   **Audio**: Instantly resolves layout-id mismatch by injecting `alcid=1` into NVRAM.
    *   **USB Mapping**: Integrated automated setup via USBToolBox with quarantine clearing.
    *   **GPU Validation**: Verify Metal acceleration and display detailed graphics info.

#### 💎 Native Experience
- **Sleek UX**: Built with SwiftUI for a responsive and truly professional macOS user experience.

---

## 📥 [Download Latest Release](https://github.com/sam4muzix/HackinTune/releases/latest/download/HackinTune_Native.zip)
*No terminal needed. Download, unzip, and run the native app!*

---

> [!IMPORTANT]
> **Safety First**: HackinTune automatically backs up your `config.plist` before any modification. Always keep a bootable recovery USB as a best practice for any Hackintosh surgery.

## 🤝 Support & Feedback
*   **GitHub Issues**: For bug reports and feature requests.
*   **Social**: Connect with the developer via [Instagram](https://www.instagram.com/shyam4muzix/) or [Email](mailto:shyam4muzix@gmail.com).

---
*© 2026 Powered by Greenmix Futech, Chennai*
