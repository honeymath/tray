# 📊 Tray Installer

This repository sets up a lightweight macOS "Tray" system for quick temporary storage.

## 📆 Installation

1. **Clone the repository**

```bash
git clone https://github.com/honeymath/tray
cd tray
```

2. **Run the installer**

```bash
mv installer.py your_favorate_dir_for_tray
cd your_favorate_dir_for_tray
python3 installer.py
```

This will create a `Tray` folder at the location where you put your installer at and install the necessary scripts (copy_to_tray.py) and a service (located at ~/Library/Services/Copy To Tray.workflow) to support tray functionality.
It will pop up the settings. Go to settings -> keyboard -> Keyboard Shortcuts -> Services -> Files and Folders -> Copy to Tray and put your favorite short cut key (I use cmd+;)


## ⚠️ Requirements

- macOS with Python 3.x (usually pre-installed)
- No third-party packages needed
