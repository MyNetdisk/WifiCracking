<div align="left">

[简体中文](https://github.com/MyNetdisk/WifiCracking/blob/main/README.zh-CN.md) | English

</div>

### 📌 Project Overview

This is a GUI-based WiFi brute-force tool written in Python using `pywifi`. It scans nearby WiFi networks and attempts to connect to a selected SSID using passwords from a dictionary file.

> ⚠️ **For educational and authorized testing use only. Do NOT use this tool for illegal purposes.**

---

### 🛠️ Requirements

* Python 3.6+
* Windows OS
* Wireless Network Card
* Administrator privileges (required to control WiFi interface)

---

### 📦 Install Dependencies

```bash
pip install pywifi
pip install comtypes
```

Or via `requirements.txt`:

```bash
pip install -r requirements.txt
```

**requirements.txt:**

```txt
pywifi>=1.1.11
comtypes>=1.1.10
```

---

### ▶️ Run the Tool

```bash
python bruteForceWifi.py
```

---

### 📚 How to Use

1. Click **Search Nearby WiFi** to scan for available networks;
2. Double-click a network in the list to autofill the SSID;
3. Click **Add Password File** and select a `.txt` dictionary file (one password per line);
4. Click **Start Cracking** to begin trying passwords;
5. If successful, the password will be shown and a popup will notify you.

---

### 📂 Example Password Dictionary

```txt
12345678
admin1234
qwertyuiop
```

---

### ❗Important Notes

* Cracking may take a long time depending on dictionary size;
* Ensure network stability;
* WPA3 encryption is **not supported**;
* **Do not attack networks without permission!**
