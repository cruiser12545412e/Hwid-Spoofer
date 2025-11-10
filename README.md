# 🛡️ HWID Spoofer - Complete System Identity Tool

<div align="center">

**Cross-platform desktop app for spoofing hardware identifiers**

![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)

</div>

---
## ✨ Features

### 🔐 **Full HWID Spoofing**
- ✅ **Machine GUID** - Windows unique identifier
- ✅ **Product ID** - Windows installation ID
- ✅ **Installation ID** - System installation identifier
- ✅ **MAC Addresses** - Network adapter spoofing

### 🌐 **Network Management**
- List all network adapters
- Random MAC generation
- Custom MAC addresses
- Reset to hardware defaults
- **Works on**: VirtualBox, VMware, USB adapters

### 🎨 **Beautiful Modern UI**
- Animated splash screen (3 seconds)
- Glassmorphism design
- Smooth Framer Motion animations
- Real-time status updates
- Toast notifications

---

## 🛠️ Tech Stack

- **Frontend**: React + TypeScript + TailwindCSS
- **Backend**: Rust + Tauri
- **Animations**: Framer Motion
- **Icons**: Lucide React

---

## 📋 Requirements

- **Node.js** (v16+) - https://nodejs.org/
- **Rust** - https://rustup.rs/
- **Windows**: Visual C++ Build Tools
- **Linux**: `build-essential libwebkit2gtk-4.0-dev`
- **macOS**: Xcode Command Line Tools

---

## 🎯 How to Use

### 1. **System Info Tab**
View your current hardware identifiers (read-only)

### 2. **Network Adapters Tab** 
- Click **"Random"** to spoof MAC address instantly
- Click **"Custom"** to enter specific MAC
- Click **"Reset"** to restore hardware MAC
- ⚠️ **Requires Administrator privileges**

### 3. **HWID Spoofing Tab** (NEW!)
- Click **"Spoof All HWIDs"** to change everything at once:
  - Machine GUID
  - Product ID
  - Installation ID
- Or spoof each individually
- ⚠️ **Requires Administrator privileges**

### Running as Administrator

**Windows**: Right-click app → "Run as administrator"  

---

## 📚 Documentation

Detailed guides in the `docs/` folder:
- **`QUICKSTART.md`** - 5-minute setup guide
- **`SETUP_GUIDE.md`** - Detailed installation
- **`HOW_TO_USE.md`** - Complete usage instructions

---

## ⚠️ Important Notes

### MAC Spoofing Compatibility
✅ **Works**: VirtualBox, VMware, USB adapters, most Ethernet  
❌ **Usually fails**: Intel Wi-Fi, modern laptop Wi-Fi cards

### HWID Spoofing
- Changes take effect immediately
- Requires administrator/root privileges
- Keep backup of original values!
- Some software may need restart to detect changes

---

## 🔧 Troubleshooting

### "Tauri API not available"
→ Run with `npm run tauri:dev`, not just `npm run dev`

### "MAC didn't change"
→ Run as administrator & try a different adapter (VirtualBox works best)

### "Build failed"
→ Close the app first, then rebuild

### Port 5173 in use
→ Close all terminals and run `run-dev.bat` again

---

## ⚖️ Legal Disclaimer

**For educational and authorized security research ONLY.**

- Use only on systems you own or have permission to test
- Unauthorized use may violate laws
- Developers assume no liability for misuse
- Intended for cybersecurity research and testing

---

## 📄 License

MIT License - See LICENSE file

---

## 🙏 Credits

Built with:
- [Tauri](https://tauri.app/) - Desktop app framework
- [React](https://react.dev/) - UI library
- [Framer Motion](https://www.framer.com/motion/) - Animations
- [TailwindCSS](https://tailwindcss.com/) - Styling

---

**Made for cybersecurity professionals and researchers** 🛡️
