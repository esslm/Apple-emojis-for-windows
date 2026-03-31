# Apple Emojis for Windows 🤯 🤩

<p align="center">
  <img src="https://img.shields.io/badge/OS-Windows%2010%20%7C%2011-blue?style=for-the-badge&logo=windows" alt="Windows Version">
  <img src="https://img.shields.io/badge/Author-Esso-cyan?style=for-the-badge" alt="Author Esso">
  <img src="https://img.shields.io/badge/Status-No--Reboot-success?style=for-the-badge" alt="No Reboot Status">
</p>

This package allows you to replace the default Windows emojis with high-resolution **Apple Color Emojis** seamlessly. Unlike traditional methods, this uses a specialized registry redirection and driver refresh, meaning **no system restart is required.**

---

## 🚀 Features

* **High Fidelity:** Uses a 37MB high-resolution `.ttf` build for crisp icons.
* **Zero Downtime:** Apply changes instantly by refreshing the font driver.
* **Safety First:** Includes a one-click uninstaller to revert to Segoe UI.
* **Cyan Aesthetics:** Custom-branded scripts with a modern developer look.

## 📦 Package Contents

| File | Description |
| :--- | :--- |
| `AppleEmoji.ttf` | The core High-Res Apple Font (37MB). |
| `InstallAppleEmojis.bat` | Automates copying, registry edits, and driver refresh. |
| `UninstallAppleEmojis.bat` | Restores default Windows emojis and cleans files. |

## 🛠️ Installation

1.  **Download** the latest release and extract the ZIP.
2.  Ensure `AppleEmoji.ttf` and the `.bat` files are in the **same folder**.
3.  Right-click `InstallAppleEmojis.bat` and select **Run as Administrator**.
4.  Your screen will blink briefly as `explorer.exe` and `fontdrvhost.exe` restart.
5.  Enjoy your new iOS-style emojis!

## 🔄 Uninstallation

If you wish to return to the original Windows emojis:
1.  Right-click `UninstallAppleEmojis.bat`.
2.  Select **Run as Administrator**.
3.  The script will handle the cleanup and restoration automatically.

## ⚠️ Troubleshooting

> [!IMPORTANT]
> **Pixelated Emojis?** > This is usually a Windows Font Cache issue. Run the `Uninstall` script, then run the `Install` script again. Ensure your Windows Scaling is set to **100%** for the sharpest results.

> [!NOTE]
> **Access Denied?**
> These scripts modify the `C:\Windows\Fonts` directory and `HKEY_LOCAL_MACHINE` registry keys. **Administrator privileges are mandatory.**

---

<p align="center">
  Developed with ❤️ by <b>Esso</b> | 2026
</p>
