# OneList CTF

**A progressive Android reverse engineering challenge with 10 flags**

## 📱 Overview

OneList is an Android todo list application that serves as a comprehensive CTF challenge covering various reverse engineering techniques. The challenge features 10 flags with progressive difficulty, starting from beginner-level static analysis and advancing to expert-level dynamic analysis, cryptography, and anti-analysis techniques.

**Difficulty**: Beginner → Expert
**Total Flags**: 10
**Flag Format**: `CYWR{...}`
**Estimated Time**: 2-8 hours (depending on experience)

## 🎯 Challenge Categories

### Static Analysis (Flags 1-5)
- **Flag 1**: Basic string discovery
- **Flag 2**: Encoded configuration data
- **Flag 3**: Metadata analysis
- **Flag 4**: Algorithm identification and reversal
- **Flag 5**: Multi-layer obfuscation

### Dynamic Analysis (Flags 6-10)
- **Flag 6**: Runtime behavior analysis
- **Flag 7**: Database interaction patterns
- **Flag 8**: Advanced cryptography and hidden assets
- **Flag 9**: Code loading mechanisms and obfuscation
- **Flag 10**: Native code analysis with steganography

## 🚀 Getting Started

### Installation
1. Download `app-release.apk` from this directory
2. Install on your device/emulator:
   ```bash
   adb install app-release.apk
   ```
3. Launch the OneList application and start exploring!

### What You Need
- Android device or emulator
- Basic reverse engineering tools (see main repository README for recommendations)
- Patience and curiosity

## 📊 Progressive Difficulty

| Flag | Category | Difficulty | Est. Time |
|------|----------|------------|-----------|
| 1 | Static | Beginner | 30 seconds |
| 2 | Static | Easy | 2 minutes |
| 3 | Static | Easy | 5 minutes |
| 4 | Static | Easy-Medium | 5 minutes |
| 5 | Static | Medium-Hard | 15 minutes |
| 6 | Dynamic | Medium-Hard | 30 minutes |
| 7 | Dynamic | Hard | 45 minutes |
| 8 | Dynamic | Very Hard | 60+ minutes |
| 9 | Dynamic | Expert | 90+ minutes |
| 10 | Dynamic | Expert | 120+ minutes |

## 📝 Flag Submission

Once you find flags, document your methodology and create a writeup! See the main repository README for submission guidelines.

## 📄 Technical Details

- **Target SDK**: 34
- **Minimum SDK**: 24
- **Build Type**: Release with aggressive obfuscation
- **Architecture**: ARM64-v8a, armeabi-v7a, x86, x86_64
- **Permissions**: Standard app permissions (no root required)

## 🙏 Credits

This CTF challenge is built upon the excellent open-source [OneList](https://github.com/lolo-io/OneList) application created by [lolo-io](https://github.com/lolo-io) and contributors. The original OneList is a clean, minimalist todo list app for Android that provided the perfect foundation for this educational reverse engineering challenge.

 - **Original Repository**: https://github.com/lolo-io/OneList
 - **License**: The original OneList project is licensed under its respective license terms
 - **Modifications**: This version has been enhanced with 10 progressive CTF challenges while preserving the core todo list functionality

Special thanks to the OneList development team for creating such a well-structured Android application that serves as an excellent learning platform for mobile security education.

---

Good luck, and may your reverse engineering skills grow stronger! 🔓

*Remember: The journey is as important as the destination. Each flag teaches valuable techniques used in real-world mobile security analysis.*