<div align="center">

# 🛡️ Bloatware Remover

### ⚡ Lightweight Android System App Manager

📱 Android · 🔍 Package Scanner · 🛡️ Shizuku Integration

<img src="assets/bloatware-remover-logo.png"
     alt="Bloatware Remover Logo"
     width="180">

**Inspect First. Understand the Risk. Remove Carefully.**

</div>

---

## 📌 About the Project

**Bloatware Remover** is a lightweight Android application designed
to help users inspect and manage pre-installed or unwanted apps
through Shizuku on supported Android devices.

The app focuses on a clean interface, package risk categories,
removal confirmation, operation history, and restore/install
options where supported.

## 📋 Project Information

| Detail | Information |
|---|---|
| 📱 Application | Bloatware Remover |
| 👨‍💻 Developer | KSU |
| 📦 Package ID | `com.curlgit.bloatwareremover` |
| 🛠️ Integration | Shizuku |
| 🌐 Internet Permission | Not required by the app |
| 📢 Advertisements | None |
| 📊 Analytics | None |
| 👤 Account | Not required |

---

## ✨ Features

- 🔍 Scan and search installed packages
- 🎨 Color-coded package risk categories
- 🛡️ Shizuku integration for supported operations
- ⚠️ Confirmation before package removal
- 🗑️ Removal operation history
- ♻️ Restore/install options where supported
- 🔄 Refresh package lists
- ⚙️ Settings and privacy details
- 📱 Lightweight interface for lower-RAM devices
- 🔐 Privacy-focused, local-first design

---

## 📥 Download APK

👉 **[📱 Download Bloatware Remover APK](https://github.com/KSURitam/Bloatware_Remover/releases/tag/Apk🥰)**

The APK is hosted on Google Drive for convenient access.

Make sure the file is shared with **Anyone with the link — Viewer**
if you want other users to download it.

---

## 🛡️ First-Time Installation & Google Play Protect

When installing an APK outside Google Play, Google Play Protect
may display a warning. This can happen when an app or its developer
is unfamiliar to Google's verification systems, but the exact
reason depends on the warning displayed.

### 📲 If a "Scan app" option appears

1. ⏳ Wait for the warning screen to load.
2. 🔍 Tap **Scan app**, if available.
3. ⏳ Wait for Google Play Protect to finish checking the app.
4. 📋 Read the result carefully.
5. ✅ If Android offers an installation option afterward, proceed
   only if you trust the APK and understand the result.

**Keep Google Play Protect enabled.** You do not need to disable it.

**⚠️ A successful scan is not an absolute guarantee of safety.
If Play Protect identifies the app as harmful, blocks installation,
or shows a warning you do not understand, do not bypass it.
Investigate the issue first**

**The wording and available options may vary by Android version
and device**

---

## 🎨 Color-Coded Risk Categories

| Color | Category | Meaning |
|---|---|---|
| 🟢 Green | Recommended Candidate | A possible removal candidate; review it first |
| 🟡 Yellow | Advanced / Caution | Research before making changes |
| 🔴 Red | Critical | Removal may affect important system functions |
| 🩷 Pink | Highly Important | Treat as especially sensitive |
| ⚪ Neutral | Unclassified | No confident category is available |

⚠️ These labels are guidance, not guarantees. Even a package marked
Recommended may be required by your particular device.

Always research unfamiliar packages before removing them.

---

## 🔐 Privacy & Security

### 💙 Privacy-First Design

Bloatware Remover is designed to perform its core package-management
operations locally on your Android device.

- 🌐 **No Internet Permission Required**  
  The app does not request Android's `INTERNET` permission.

- 🚫 **No Advertisements**  
  No in-app advertising is included.

- 📊 **No Analytics**  
  No analytics tracking is included.

- 🐞 **No Crash Reporting**  
  No crash-reporting service is included.

- 👤 **No Account Required**  
  No registration or sign-in is needed.

- 📱 **Local Package Information**  
  Installed-package information is accessed locally through Android.

- 🗂️ **Private Local History**  
  Operation history and settings are stored in the app's private
  storage.

- 🛡️ **Shizuku Integration**  
  Supported privileged operations use Shizuku authorization.

- 💤 **No App Background Service When Closed**  
  The app is designed not to run its own background service
  while it is closed.

### 🌐 Does the App Need Internet?

The app does not request the Android `INTERNET` permission.
Its core package-management functionality is designed to work locally.

Android, Shizuku, and other installed system components operate
separately, so this statement does not mean the entire device
is offline.

These privacy claims should be checked against the released APK's
manifest and implementation.

---

## ⚙️ Setup Guide

### 🌱 Rooted Android

1. 📲 Install and open Shizuku.
2. Select **Start via Root**, if available.
3. ✅ Approve the request in your root manager.
4. ⏳ Wait until Shizuku reports that its service is running.
5. 🛡️ Open Bloatware Remover.
6. 🔓 Grant Shizuku authorization when prompted.

If Shizuku starts successfully through root, Wireless Debugging
is not required for that startup method.

> ℹ️ Starting Shizuku through root does not automatically make
> Bloatware Remover itself a root application.

### 📶 Non-root Android

1. Install Shizuku.
2. Follow the official setup instructions.
3. Enable Wireless Debugging if required by your setup method.
4. Start the Shizuku service.
5. Open Bloatware Remover and authorize access.

📚 Official guide:
https://shizuku.rikka.app/guide/setup/

---

## 🚀 How to Use

1. 📖 Open the app and read the disclaimer.
2. 🔍 Scan the installed packages.
3. 🧾 Select a package and review its category.
4. 🌐 Research unfamiliar packages before making changes.
5. ⚠️ Confirm removal only if you understand the consequences.
6. ♻️ Use Restore / Install where supported.

---

## 📸 Screenshots & Testing Evidence

### 🛡️ Shizuku Integration

The Settings screen displays Shizuku installation, service,
authorization, and connection status.

### 🗑️ Package Removal History

The developer's screenshots show a recorded operation for:

- **Application:** Bookmark Provider
- **Package:** `com.android.bookmarkprovider`
- **Recorded result:** `uninstall succeeded`
- **Reported state:** Not installed for the current user

### ♻️ Restore / Install

The Restore / Install screen displays packages that are not
installed for the current user and may be restorable if the system
still retains them.

### 🧪 Testing Status

The developer reports that testing has been completed on their
device and the tested features are working.

Reported results include:

- ✅ Application launches successfully
- ✅ Disclaimer and privacy details appear
- ✅ Risk-category labels are displayed
- ✅ Shizuku-based package removal works on the tested setup
- ✅ Removal confirmation is displayed
- ✅ Operation history records removal results
- ✅ Restore / Install displays eligible packages

These are developer-reported results, not a guarantee that every
feature works identically on every Android device.

---

## 💡 Inspiration & Credits

### 🧹 Canta

🔗 https://github.com/samolego/Canta

Canta inspired aspects of the general Android debloating workflow
and the goal of making package management easier for users.

### 🛠️ Shizuku

🔗 https://shizuku.rikka.app/

Shizuku provides the service used for supported operations requiring
Shizuku-authorized privileges.

### 🧰 Universal Android Debloater Next Generation

🔗 https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation

Acknowledged as a related community project within the Android
debloating ecosystem.

### 📜 Attribution Notice

Bloatware Remover is an independent project developed by **Curlgit**.

It is not an official release of, or affiliated with, Canta,
Shizuku, or Universal Android Debloater Next Generation.

These credits acknowledge inspiration, technology, or related work.
They do not imply endorsement or partnership.

Third-party source code, graphics, icons, and other assets must be
used according to their applicable licenses and permissions.
A referenced project's license does not automatically apply
to Bloatware Remover.

---

## ⚠️ Disclaimer

Removing system packages can disable device features, cause
instability, remove dependencies, or prevent the device from
starting normally.

- 💾 Back up important data before system-level changes.
- 🔍 Research unfamiliar packages before removing them.
- 🟢 Never assume a Recommended label guarantees safety.
- 🧰 Keep a recovery plan suitable for your device.
- 🛡️ Do not ignore security warnings about downloaded APKs.
- 👤 You are responsible for changes made to your device.

Bloatware Remover is provided **"AS IS"**, without guarantees
of safety or fitness for a particular purpose, to the extent
permitted by applicable law.
