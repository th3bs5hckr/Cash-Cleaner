# Cash Cleaner (cc) 🧹

**Cash Cleaner** is a lightweight, powerful shell script designed for rooted Android devices running Termux. It aggressively clears system and app cache files that standard cleaners can't reach, helping you reclaim valuable storage space instantly.

---

## 🚀 Features
* **Root-Powered:** Accesses restricted system directories to clear stubborn caches.
* **Termux Native:** Built specifically for command-line efficiency.
* **Global Command:** Once installed, just type a simple two-letter command to clean your device.

---

## 🛠️ Installation & Setup

To get started, make sure you have **Termux** installed and **Root access** granted.

1. Download the `cc` script to your device's `Download` folder.
2. Open Termux and run the following commands to install it:

```bash
cp /sdcard/Download/cc $PREFIX/bin/cc
chmod +x $PREFIX/bin/cc
cc