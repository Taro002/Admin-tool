# Admin Control Menu (Windows)

A lightweight **Windows administration menu** written in Batch, designed to centralize common system management tasks in a single, simple interface.

This tool is intended for **advanced users**, sysadmins, and power users who want quick access to diagnostics, maintenance, and repair commands without navigating multiple Windows tools.

---

## Features

* Automatic **administrator privilege escalation**
* Centralized menu-driven interface
* System information overview
* Process listing and termination
* User account listing
* Network diagnostics
* Temporary files cleanup
* Windows system repair (`SFC` / `DISM`)
* Disk management via DiskPart (**high risk**)
* Action logging for traceability

---

## Getting Started

### Requirements

* Windows 10 or Windows 11
* Administrator privileges

### Usage

1. Download `admin.bat`
2. Right-click → **Run as administrator**
3. Select an option from the menu using the corresponding number

---

## Menu Overview

* **System Info** – Displays detailed system configuration
* **Processes** – Lists running processes
* **Kill Process** – Force-terminate a process
* **Users** – Lists local user accounts
* **Network** – Full network configuration
* **Services** – Lists Windows services
* **Cleanup** – Deletes temporary system files
* **Repair Windows** – System integrity and image repair
* **DiskPart** – Low-level disk operations (**dangerous**)

---

## Logging

All critical actions are logged to:

```
admin_log.txt
```

This includes authentication attempts, system checks, cleanup operations, and disk actions.

---

## Security Notes

* Administrator rights are mandatory
* Disk operations can **irreversibly erase data**
* This tool should only be used on systems you own or manage

---

## Compatibility

* Windows 10
* Windows 11

Not compatible with Linux or macOS.

---

## Disclaimer

This project is provided **as-is**.
The author is not responsible for data loss, system damage, or misuse.

---

## License

Copyright © 2025 Taro

Open-source project.
Free to use, modify, and redistribute.

---

![Platform](https://img.shields.io/badge/OS-Windows%2010%20%7C%2011-blue)
![Shell](https://img.shields.io/badge/Shell-Batchfile-lightgrey)
![Maintained](https://img.shields.io/badge/Maintained-yes-success)
![Security](https://img.shields.io/badge/Admin%20Required-Yes-critical)

