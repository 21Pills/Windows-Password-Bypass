# Windows-Password-Bypass
Used Hiren's Boot CD (WinPE environment) to bypass a forgotten Windows login password by booting from external media, accessing the system drive externally, and resetting the local user account password without needing to log into the OS.
# Windows Password Recovery with Hiren's Boot CD

A personal documentation of how I bypassed a forgotten Windows Microsoft account 
password using Hiren's Boot CD.

## 🛠️ Tools Used
- [Hiren's Boot CD](https://www.hirensbootcd.org/)
- Rufus (https://rufus.ie)
- Windows PE Environment
- Command Prompt (Admin)
-16GB USB Flash Drive
-Computer/Laptop with Internet Access

## 📋 Overview
Booted into a WinPE environment using Hiren's Boot CD to access the system 
drive externally and reset a forgotten Windows local account password — 
without needing to log into the OS.

## 🔧 Steps
1. Download Hiren's Boot CD ISO and Rufus. <img width="4720" height="1272" alt="image" src="https://github.com/user-attachments/assets/de2c178a-be6a-49ea-9376-d924740ce778" /><img width="876" height="279" alt="image" src="https://github.com/user-attachments/assets/0166199f-6efc-4b20-a0b5-50605d2eb7ec" />

2. Open Rufus. Ensure your USB drive is selected in the Device section. Select the Hiren's Boot CD ISO you downloaded.

4. Click Start and allow the process to complete.
   <img width="484" height="551" alt="image" src="https://github.com/user-attachments/assets/298eda2f-693a-4dc8-bd43-5e7a5ebba431" />**
   
5. Hold Shift while clicking Restart on the target PC. Naviagte to UEFI Firmware Settings.
   <img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/e1075e62-bfd0-4f51-9f14-57669c2afeb0" /><img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/f4970291-3790-46eb-a51c-e5dbe07656c0" />
<img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/15689f12-0c8b-4d2a-a2b8-309a6dd679f9" />
Click on "UEFI Firmware Settings".

5a. Select "Boot Menu".
<img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/76b3b59f-8ddc-44f5-bfc9-4295ae74237b" />

5b. Select your USB.
<img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/28077742-99ca-4d6f-8bfe-2469db853c1f" />
Please allow your Device time to boot safely into the USB.

6.Once in the WinPE environment, open the Start Menu (Windows logo, bottom left). Navigate to All Programs → Security → Passwords → Windows Login Unlocker. 
**<img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/24c22d18-a38d-4af5-9d2a-dbef2b1b462a" />
<img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/d54be9bd-9ad7-4796-9406-8b2d7e5bae08" />

7. Before proceeding, ensure BitLocker is disabled on the C: drive. If the drive is encrypted, no Windows user accounts will be visible.
   <img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/36fd7882-cb84-4a8e-bd88-9c4e0030a4a8" />
   
8. In Windows Login Unlocker, select the user account you want to modify. Click Bypass (bottom right) to generate a one-time login bypass. Use that session to reset the account password.
<img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/20e5f1aa-c222-4fc8-ba57-910895774cc5" />

9. Reboot into Windows normally

## ⚠️ Disclaimer
This is for **educational purposes only**. Only use this on systems you own 
or have explicit permission to access. Unauthorized access to computer systems 
is illegal.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) 
file for details.
