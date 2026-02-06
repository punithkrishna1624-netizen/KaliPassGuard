# KaliPassGuard
Password Strength Tester Tool for Kali Linux
# KaliPassGuard - Password Strength Tester Tool for Kali Linux

KaliPassGuard is a custom ethical cybersecurity tool developed in Python 3
for Kali Linux users to test and evaluate password strength.

This tool is designed to help students, penetration testers, and security
professionals understand how strong or weak a password is based on common
security rules used in real-world environments.

---

## 🔥 Key Features

- Fully CLI-based tool (works in Kali Linux terminal)
- Built using Python 3 with modular and clean design
- Uses argparse for professional command-line argument handling
- Provides colored output for better readability
- Displays a progress bar during password analysis
- Evaluates password strength based on:
  - Minimum length requirements
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special symbols (!@#$%^&*)
- Calculates password entropy (randomness score)
- Gives improvement suggestions for weak passwords
- Automatically saves results into a TXT report file
- Includes banner, version information, and help menu

---

## 🛠 Required Libraries

Install dependencies before running:

```bash
pip3 install colorama tqdm
