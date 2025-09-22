# Android Reverse Engineering CTFs

Welcome to the Android Reverse Engineering CTF repository by **Cynychwr (Daniel Oliveira)**!

This repository contains a collection of Android-focused Capture The Flag (CTF) challenges designed to teach and test various reverse engineering skills including static analysis, dynamic analysis, cryptography, obfuscation techniques, and mobile security concepts.

## 🎯 About

These CTFs are created to provide hands-on experience with:
- **Static Analysis**: APK decompilation, code analysis, resource inspection
- **Dynamic Analysis**: Runtime behavior, debugging, instrumentation
- **Cryptography**: Various encoding/encryption techniques
- **Anti-Analysis**: Obfuscation, packing, detection evasion
- **Mobile Security**: Android-specific vulnerabilities and techniques

## 🚩 Available CTFs

| CTF Name | Difficulty | Flags | Description | Status |
|----------|------------|-------|-------------|--------|
| [OneList](./onelist/) | Beginner → Expert | 10 | Android todo app with progressive difficulty flags | ✅ Available |

## 📝 Submission Guidelines

Found all the flags? Want to share your writeup? Here's how to get recognized:

### How to Submit Solutions

1. **Complete the CTF** - Find all (or partial) flags from any available CTF
2. **Create a Writeup** - Document your solution process. This can be:
   - A blog post on your personal website
   - A GitHub repository with detailed analysis
   - A Medium article or similar platform
   - Any public documentation of your approach

3. **Submit via LinkedIn** - Send me a message on LinkedIn with:
   - Your GitHub username
   - Link to your writeup
   - Which CTF you completed and how many flags you found
   - **LinkedIn**: [in/danielsadoliveira/](https://www.linkedin.com/in/danielsadoliveira/)

### What Makes a Good Writeup?

- **Clear methodology** - Explain your analysis approach
- **Tools used** - Mention the tools and techniques employed
- **Screenshots/evidence** - Show your work with relevant images
- **Step-by-step process** - Help others learn from your approach
- **Challenges faced** - Discuss difficulties and how you overcame them

## 🏆 Recognition

Successful submissions will be added to each CTF's **WALL.md** (Wall of Fame) with:
- Your name linked to your GitHub profile
- Link to your writeup
- Completion status (Full/Partial)
- Submission date

## 🛠 Getting Started

Each CTF directory contains:
- **README.md** - CTF description, setup instructions, and hints
- **WALL.md** - Wall of fame for successful submissions
- **Release files** - APK and any required resources

## 📋 General Tips

- **Use multiple tools** - Different tools reveal different information
- **Static + Dynamic** - Combine both analysis approaches
- **Take notes** - Document your findings as you go
- **Read the code** - Understanding the implementation is key
- **Be patient** - Some flags require multiple steps or conditions

## 🔧 Recommended Tools

### Static Analysis
- [jadx](https://github.com/skylot/jadx) - DEX to Java decompiler
- [apktool](https://ibotpeaches.github.io/Apktool/) - APK reverse engineering
- [Mobile Security Framework (MobSF)](https://github.com/MobSF/Mobile-Security-Framework-MobSF)

### Dynamic Analysis
- [Frida](https://frida.re/) - Dynamic instrumentation
- [ADB](https://developer.android.com/studio/command-line/adb) - Android Debug Bridge
- [Genymotion](https://www.genymotion.com/) or Android Emulator

### General Tools
- [CyberChef](https://gchq.github.io/CyberChef/) - Data encoding/decoding
- [Ghidra](https://ghidra-sre.org/) - For native library analysis
- Hex editors, string analysis tools

## 📞 Contact

- **LinkedIn**: [in/danielsadoliveira/](https://www.linkedin.com/in/danielsadoliveira/)
- **Email**: danielsadoliveira@gmail.com

## ⚖️ License & Disclaimer

These CTFs are provided for educational purposes only. Use the techniques learned responsibly and only on applications you own or have explicit permission to test.

---

Happy hacking! 🔓