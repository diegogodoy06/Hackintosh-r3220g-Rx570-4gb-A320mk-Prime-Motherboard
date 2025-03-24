# Hackintosh-r3220g-Rx570-4gb-A320mk-Prime-Motherboard
OpenCore Hackintosh EFI for R3 2200G + RX 570 + ASUS A320M-K PRIME

![image](https://github.com/user-attachments/assets/eb5f70f0-c1c6-4bc0-9734-b944a4dd8096)![image](https://github.com/user-attachments/assets/b176f0dc-a8c6-4062-a141-df805f252f13)

## 📋 Overview

This repository contains detailed information about the EFI installation, where I used **OpenCore Simplify** to configure most of the EFI.

---

## 🖥️ System Info

| **Item**                   | **Information**                                   |
|----------------------------|---------------------------------------------------|
| **Host**                   | Diegos-iMac-Pro.home                              |
| **Operating System**       | Sequoia Version 15.3.2 (Build 24D81)                      |
| **Kernel**                 | Darwin 24.3.0 x86_64                              |
| **RAM**                    | 16.00 GB                                          |
| **Model Identifier**       | iMacPro1,1                                        |
| **CPU**                    | AMD Ryzen 3 2200G with Radeon Vega Graphics       |
| **VDA Decoder**            | Fully Supported                                   |

---

## 📇 Serial Info

| **Item**                   | **Information**                                   |
|----------------------------|---------------------------------------------------|
| **Year**                   | 2021                                             |
| **Model**                  | iMac Pro (2017)                                  |
| **Model Identifier**       | iMacPro1,1                                       |
| **Valid**                  | Possibly                                         |

---

## 🎨 GFX0

| **Item**                   | **Information**                                   |
|----------------------------|---------------------------------------------------|
| **GPU Name**               | Ellesmere [Radeon RX 470/480/570/570X/580/580X/590] |
| **GPU ID**                 | 0x67DF1002                                       |
| **Quartz Extreme (QE/CI)** | Yes                                              |
| **Metal Supported**        | Yes                                              |
| **Metal Device Name**      | AMD Radeon RX 570                                |
| **Metal Default Device**   | Yes                                              |
| **Metal Low Power**        | No                                               |
| **Metal Headless**         | No                                               |

---

## 🛠️ BIOS Settings

### Disable
- Fast Boot
- Serial/COM Port
- Hyper-Threading

### Enable
- Secure Boot auto
- Compatibility Support Module (CSM)
- Above 4G decoding
- EHCI/XHCI Hand-off
- OS type: Others
- SATA Mode: AHCI

---

## 🔧 Additional Information

- **OpenCore Simplify:**  
  Used to create most of my EFI.  
  Official repository: [OpenCore Simplify](https://github.com/OpenCore-Simplify/OpenCore-Simplify)  
  ![OpenCore Simplify](https://img.shields.io/badge/OpenCore-Simplify-blue?style=flat-square)
