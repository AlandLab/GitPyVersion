CLI utility for Windows to check and update Git and Python - Freeware.
**Languages / Lingue:** [English](#description-english) | [Italiano](README_it.md)
# 🛠️ GitPyVersion

*Version*: 1.0  
*License*: Freeware  
*Copyright © 2025 AlandLab*

---

## 📝 Description

GitPyVersion is a command-line utility for Windows that checks the installed versions of `Git` and `Python` and, if updates are available, allows downloading and installing them quickly.

---

## ✨ Main features

- Checks the versions of Git and Python installed on the system.  
- Automatically extracts the latest available versions from the official Git and Python pages.  
- Downloads and, if requested, installs new versions (`-d` to download, `-di` to download and install).    
- Installs Git and/or Python if missing on the system.  
- Shows a progress bar during downloads.

---

## ⚡ Installation

1. Download the latest `GitPyVersion`.  
2. Copy the file to a folder of your choice.  
3. You can rename the executable to a shorter name, for example `gpv.exe`; all options will adapt automatically to the new name.

* Redistribution with a modified name is not allowed.

---

## 💡 Usage
```text
GitPyVersion.exe [option] [target]
```

### ⚙️ Options

| Option            | Description                                                                    |
| ----------------- | ------------------------------------------------------------------------------ |
| `-h`, `--help`    | Show this help message.                                                        |
| `-v`, `--version` | Show the program version.                                                      |
| `-l`, `--license` | Show the license and instructions for viewing third‑party licenses.            |
| `-d`              | Download the update for the target.                                            |
| `-di`             | Download and install the update for the target.                                |
| `-ad`             | Download updates for both targets.                                             |
| `-adi`            | Download and install updates for both targets.                                 |

### 🎯 Target

| Target         | Description      |
| -------------- | ---------------- |
| `git`          | Update Git.      |
| `py`, `python` | Update Python.   |

---

## 📌 Examples

- Download the update for Git: `GitPyVersion.exe -d git`  
- Download and install the update for Python: `GitPyVersion.exe -di py`  
- Download updates for Git and Python: `GitPyVersion.exe -ad`  
- Download and install updates for Git and Python: `GitPyVersion.exe -adi`

---

## 👤 Author

AlandLab  
✉️ [AlandLab3@Gmail.com](mailto:AlandLab3@Gmail.com)  
📍 (PV) Italy

---

## 🔄 Future update check

If problems occur when detecting versions (due to structural changes to the official Git or Python websites), check for updates to GitPyVersion.

---

## 📄 License

This software is released free of charge and may be used and redistributed without modification.  
For full details, see `LICENSE.txt` and `THIRD_PARTY_LICENSES.txt`.
