# Hackintosh-r3220g-Rx570-4gb-A320mk-Prime-Motherboard
OpenCore Hackintosh EFI for R3 2200G + RX 570 + ASUS A320M-K PRIME

[![OpenCore Legacy Patcher](https://img.shields.io/badge/OpenCore%20Legacy%20Patcher-Repo-blue?logo=github)](https://github.com/dortania/OpenCore-Legacy-Patcher)  [![Dortania Docs](https://img.shields.io/badge/Dortania%20Docs-Website-orange?logo=readthedocs)](https://dortania.github.io/docs/)  [![OCAuxiliaryTools](https://img.shields.io/badge/OCAuxiliaryTools-Repo-blue?logo=github)](https://github.com/ic005k/OCAuxiliaryTools)  [![Hackintool](https://img.shields.io/badge/Hackintool-Repo-blue?logo=github)](https://github.com/benbaker76/Hackintool)   ![OpenCore Simplify](https://img.shields.io/badge/OpenCore-Simplify-blue?style=flat-square)

![image](https://github.com/user-attachments/assets/eb5f70f0-c1c6-4bc0-9734-b944a4dd8096)

## Screenshot
<details>
  <summary><strong>Click to expand</strong></summary>

  ![Screenshot 1](/Hackintool01.png)

</details>


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
