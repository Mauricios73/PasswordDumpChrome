# Cybersecurity Tools: DuckyScript Password Stealer (Educational)

## 🚨 Warning: Educational Purposes Only
This repository contains a DuckyScript code used for educational purposes to demonstrate how attackers can potentially steal passwords from Chrome browsers on Windows 10. It is intended for security researchers, ethical hackers, and cybersecurity students to learn more about cybersecurity practices.

**DO NOT use this script for malicious purposes.** Unauthorized access to computer systems is illegal and unethical.

## 🛠️ Requirements
- Windows 10 machine
- [DigiKeyboard](https://github.com/matrixes/DigiKeyboard) library to emulate keystrokes (for use with Arduino or other USB devices)
- Chrome browser installed
- PowerShell for email sending configuration

## 💡 How It Works
This script emulates keystrokes on a target machine and performs the following actions:
1. Opens Chrome browser via Windows + R command and types the URL for saved passwords.
2. Navigates through Chrome's password settings.
3. Extracts password data and saves it to a CSV file.
4. Sends the CSV file via email using PowerShell and Gmail's SMTP server.

## 📝 Instructions
1. Clone this repository.
2. Upload the script to an Arduino or similar device capable of sending keystrokes.
3. Execute the script on a machine running Windows 10 with Chrome installed.
4. Ensure you have enabled "Less secure app access" on your Gmail account: [Link to Google Settings](https://myaccount.google.com/lesssecureapps).
5. The script will retrieve Chrome passwords and email them to the predefined recipient.

## 📚 Tutorials and Guides
- [How to Use DigiKeyboard with Arduino](https://www.arduino.cc/reference/en/libraries/digikeyboard/)
- [Ethical Hacking Basics](https://www.eccouncil.org/)
- [Secure Your Passwords](https://www.csoonline.com/article/3153233/11-tips-for-keeping-your-passwords-secure.html)

# Contributing to Cybersecurity Tools Repository

Thank you for considering contributing to this project! We welcome your contributions.

## Guidelines
- **Educational Use Only**: The code in this repository should only be used for educational, ethical hacking, or research purposes. Malicious usage is strictly prohibited.
- **Issues**: If you encounter a bug or have a feature request, feel free to create an issue.
- **Pull Requests**: If you have improvements or fixes, please open a pull request. Ensure that your code is well-documented and tested.

## Code of Conduct
Please adhere to a high standard of conduct in all interactions. Be respectful, helpful, and constructive.

## Steps to Contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.


# 💬 Disclaimer
This script is for educational purposes only. Ensure you have permission before using this script on any machine. Unauthorized use can lead to legal consequences.

---

## 💼 Author
Mauricio Portela - Cybersecurity professional with experience in ethical hacking and digital security practices.

