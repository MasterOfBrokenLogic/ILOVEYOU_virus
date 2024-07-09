# ILOVEYOU VBScript

[![Educational](https://img.shields.io/badge/Purpose-Educational-blue)](https://github.com/yourusername/iloveyou-vbs)
[![Dangerous](https://img.shields.io/badge/Warning-Dangerous-red)](https://github.com/yourusername/iloveyou-vbs)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Description

This repository contains the infamous ILOVEYOU virus script, written in VBScript. This code is provided for educational and research purposes only, to help understand how such scripts function and the damage they can cause.

**Warning:** This script is dangerous. Executing it on your machine can cause significant harm to your files and system. Do not run this script on any system you care about.

## How It Works

The script performs the following actions:

1. **Initial Setup**: 
   - Reads its own content and prepares to replicate.
   - Disables Windows Scripting Host Timeout to ensure it can run indefinitely.

2. **Replication**:
   - Copies itself to critical system directories (`C:\Windows\` and `C:\Windows\System32\`) with different names.
   - Adds entries to the Windows registry to ensure it runs on system startup.

3. **File Infection**:
   - Scans the drives and directories for specific file types (`.vbs`, `.vbe`, `.js`, `.jse`, `.css`, `.wsh`, `.sct`, `.hta`, `.jpg`, `.jpeg`, `.mp3`, `.mp2`).
   - Overwrites or renames these files with a copy of the malicious script.

4. **Email Spreading**:
   - Uses Outlook to send emails to all contacts in the address book with the infected script as an attachment.

5. **Web Interaction**:
   - Modifies the Internet Explorer start page to point to various malicious URLs.

6. **HTML Payload**:
   - Creates an HTML file with embedded VBScript to propagate the virus further.

## Usage

This script is provided for **educational purposes only**. Do not run this script on any real system. You can examine the script to understand how it operates.

### Precautions

- **Do not execute this script on your main machine.**
- **Use a virtual machine or isolated environment for testing.**
- **Ensure your antivirus software is up to date.**
- **Backup your data before experimenting with such scripts.**

## Warnings

- **Running this script will cause irreversible damage to your files and operating system.**
- **This script will spread itself via email, potentially affecting other systems.**
- **You are responsible for any damage caused by executing this script.**

## Educational Purpose

This repository is intended to provide a learning resource on how malicious scripts can operate and the importance of cybersecurity. It should be used responsibly and ethically.

## How It Will Affect Your PC

If executed, the script will:

- **Overwrite and delete various file types** on your system.
- **Replicate itself** in multiple locations and ensure it runs on startup.
- **Send emails** to your contacts, spreading the infection.
- **Change your browser settings** to point to malicious websites.
- **Potentially render your system unusable** due to the extent of the modifications and deletions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
