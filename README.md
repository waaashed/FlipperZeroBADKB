# Disable Windows Defender and Run Python Script (PoC)

This project provides an automated Proof-of-Concept script to simulate the deactivation of Windows Defender and the silent execution of a Python program using PowerShell.  
It's designed to demonstrate how physical attack vectors like BadUSB can be leveraged in offensive security scenarios.

---

## Features

- Automates Windows Defender deactivation
- Launches elevated PowerShell in hidden mode
- Downloads and extracts a ZIP file from a GitHub repository
- Installs Python dependencies via `pip`
- Executes a Python script silently

---

## How It Works

This script emulates keyboard input to perform the following actions:

1. Opens Windows Security settings
2. Navigates through menus to disable real-time protection
3. Minimizes the UI to hide evidence
4. Runs `powershell.exe` with admin rights and hidden window
5. Downloads and executes your custom Python payload

---

## Setup

Before running this script, **you must**:

- Replace the placeholder values:
  - `LINK TO YOUR GITHUB REPOSITORY`
  - `YOUR FILE NAME.zip`
  - `YOUR FILE NAME`, `YOUR FILE NEW NAME`
  - `YOUR PROGRAM NAME.py`

> **Don't forget to modify the code to suit your use.**

---

## Legal Notice

> [!WARNING]  
> This program is provided for **educational and research purposes only**.  
> Any unauthorized or malicious use of this script is strictly prohibited and may violate local, national, or international laws. The author assumes **no responsibility** for misuse.

---

## Credits

Author: `s0d3ep (v1.0)`  
Platform: Windows 10/11

---

Feel free to fork, adapt, and explore this for **defensive testing, PoC development**, or **training environments**.
