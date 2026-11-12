# Harsta Releases

This public repository is dedicated exclusively to the official binary distribution of **Harsta**, the native Windows Dynamic Notch application.

> **Note:** The proprietary source code and development assets for Harsta are maintained in private development repositories. This repository contains only verified, public distribution binaries and cryptographic checksums.

---

## Official Latest Download

| Asset | Description | Direct Download |
| :--- | :--- | :--- |
| **`HarstaSetup.exe`** | Official Windows Installer (x64) | [Download Installer](https://github.com/Harunsatr/HarstaReleases/releases/latest/download/HarstaSetup.exe) |
| **`HarstaSetup.exe.sha256`** | SHA-256 Checksum Verification File | [Download Checksum](https://github.com/Harunsatr/HarstaReleases/releases/latest/download/HarstaSetup.exe.sha256) |

---

## Verifying Installer Integrity

Before running the installer, you can independently verify its cryptographic integrity using Windows PowerShell:

```powershell
Get-FileHash -Path .\HarstaSetup.exe -Algorithm SHA256
```

### Stable Release v1.0.0 Checksum
```text
50949B9676FCA36ABAE057605ABE351E3822CBCC0200F92106B3FA8242A401E0
```

---

## System Requirements

- **Operating System:** Windows 10 Version 1809 (Build 17763) or newer / Windows 11 (21H2+)
- **Architecture:** x64 (64-bit)
- **Privileges:** Standard user (`asInvoker` â€” no administrator privileges required)
- **Telemetry:** Zero telemetry, zero tracking, zero keylogging.

---

## Windows SmartScreen Notice

Harsta is an independent developer project distributed without a costly commercial Extended Validation (EV) certificate. If Windows SmartScreen displays a warning (*"Windows protected your PC"*):
1. Click **"More info"**.
2. Click **"Run anyway"**.
3. Verify that the SHA-256 hash matches the published checksum above.

---

## Official Website & Support

- Website: [https://harsta.app](https://harsta.app)
- Issues & Inquiries: Through the official Harsta website support portal.
