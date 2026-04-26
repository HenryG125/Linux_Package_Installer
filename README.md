# Linux_Package_Installer
# Linux Package Installer

A simple and powerful GUI tool for installing applications on Debian-based systems like Kali Linux.

## 🚀 Features

* Install multiple applications at once
* Clean GUI (no terminal needed)
* Organized categories:

  * Browsers
  * Utilities
  * Package Managers
  * Games
* Supports advanced installs:

  * Google Chrome (.deb download & install)
  * Spotify (repository setup included)
  * Flatpak (with Flathub)
  * Snap (auto-enable service)
  * Python Pip
* Real-time installation output
* Single password prompt using `pkexec`

---

## 🖥️ Supported Systems

* Kali Linux
* Debian-based distributions
* Ubuntu (should work)

---

## 📦 Included Software

### Browsers

* Google Chrome
* Tor Browser Launcher

### Utilities

* GIMP, VLC, Git, Curl
* Terminator, LibreOffice
* Wget, MenuLibre
* Spotify

### Package Managers

* Snap
* Flatpak
* Python Pip
* Homebrew (Advanced)

### Games

* GNOME Mines

---

## ⚙️ Requirements

* Python 3
* `tkinter` (usually pre-installed)
* Internet connection
* Admin privileges (sudo / pkexec)

---

## ▶️ How to Run

```bash
python3 Linux_Package_Installer.py
```

---

## 🔐 Notes

* You will be prompted **once** for your password
* Some installs (like Homebrew) may take longer
* Snap is automatically enabled if selected
* Flatpak includes Flathub repository setup

---

## 📁 File Structure

```
Linux_Package_Installer.py
README.md
```

---

## 🛠️ Future Improvements

* Progress bar per package
* Auto-detect installed apps
* Save user selections
* Add more software (Brave, Discord, etc.)
* UI enhancements (icons, collapsible sections)

---

## 👨‍💻 Author

Henry Garcia

---

## 📄 License

Free to use and modify.

