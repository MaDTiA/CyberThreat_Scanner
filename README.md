MaDTiA: Cyber Threat Scanner v1.0
-----------------------------------
Description:
A Python-based cyber threat scanner designed for Windows systems. It scans for malware by detecting suspicious files with double extensions in common directories, checks startup entries for known threats, and provides options to quarantine, delete, or ignore detections.

Features:
- Scans local drive(s) and common folders (Desktop, Downloads, Documents, etc.)
- Detects files with double extensions indicative of malware.
- Monitors startup folder for malicious executables.
- Automatically attempts to remove suspicious registry and scheduled task entries.
- Safe deletion with a retry mechanism.
- Cyberpunk-style interface with a colorful ASCII banner.

Requirements:
- Windows operating system
- Python 3.x
- Required Python packages: colorama, psutil, pywin32
- Administrator privileges to run the script

Usage:
1. Install Python 3.x if not already installed.
2. Install the required packages:
   pip install colorama psutil pywin32
3. Run the script with administrator privileges:
   python script.py

Disclaimer:
This tool is intended for educational purposes and authorized use only. Use it at your own risk.

Credits:
Developed by MaDTiA. For more details, visit:
   Portal: https://madtia.cc
   GitHub: https://github.com/MaDTiA
