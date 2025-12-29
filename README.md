# 🔒 SecureVault - Local Password Manager

A beautiful, secure, client-side password manager built for privacy-conscious users. No server, no cloud, no tracking - your passwords never leave your device.

![SecureVault Banner](https://img.shields.io/badge/encryption-AES--256-green) ![License](https://img.shields.io/badge/license-MIT-blue) ![Browser](https://img.shields.io/badge/browser-any-orange)

## ✨ Features

- **🔐 Military-Grade Encryption**: AES-256 encryption keeps your passwords secure
- **💻 100% Local**: Everything runs in your browser - no servers, no cloud sync
- **🎨 Beautiful Interface**: Modern, dark-themed UI designed for usability
- **🎲 Password Generator**: Create strong, random passwords with customizable options
- **📊 Password Strength Analysis**: Real-time feedback on password security
- **📁 Category Organization**: Organize passwords by Bug Bounty, Social Media, Email, Banking, Work, and more
- **🔍 Fast Search**: Quickly find any password with instant search
- **📥 Import/Export**: Backup and restore your vault with JSON exports
- **🚀 Zero Installation**: Just open the HTML file - no installation required
- **🔒 Auto-Lock**: Secure your vault when you're done

## 🚀 Quick Start

### Method 1: Download and Open
1. Download `password_manager.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Create your master password
4. Start adding passwords!

### Method 2: Clone Repository
```bash
git clone https://github.com/yourusername/securevault.git
cd securevault
open password_manager.html
```

That's it! No dependencies, no build process, no npm install - just open and use.

## 📖 How It Works

### First Time Setup
1. Open `password_manager.html` in your browser
2. Create a strong master password (minimum 8 characters)
3. Your vault is now ready to use!

### Adding Passwords
1. Click "Add Password"
2. Fill in the details (title, username, password, etc.)
3. Use the 🎲 button to generate a strong random password
4. Choose a category to organize your passwords
5. Save and you're done!

### Accessing Passwords
1. Search for any password using the search bar
2. Filter by category in the sidebar
3. Click 👁️ to reveal a password
4. Click 📋 to copy username or password to clipboard
5. Lock your vault when you're done with the 🔒 button

## 🔐 Security Features

### Encryption
- **Algorithm**: AES-256 (Advanced Encryption Standard)
- **Key Derivation**: Your master password is hashed with SHA-256
- **Storage**: Encrypted data is stored in browser localStorage
- **No Transmission**: Nothing is ever sent to any server

### Best Practices
- ✅ Use a strong, unique master password
- ✅ Lock your vault when stepping away
- ✅ Export regular backups
- ✅ Keep backups in a secure location
- ⚠️ **IMPORTANT**: If you lose your master password, your data cannot be recovered

## 💾 Backup & Restore

### Export Your Vault
1. Click "Export Vault" in the sidebar
2. Save the JSON file in a secure location
3. Consider encrypting the backup file itself for extra security

### Import Your Vault
1. Click "Import Vault" in the sidebar
2. Select your backup JSON file
3. Imported passwords will merge with existing ones

## 🎯 Use Cases

- **Bug Bounty Hunters**: Store credentials for testing platforms securely
- **Developers**: Keep API keys, database passwords, and service credentials safe
- **Privacy Advocates**: No cloud sync means no data breaches
- **General Users**: Secure all your online accounts without trusting a third party
- **Offline Use**: Works completely offline once loaded

## 🛠️ Technical Details

### Built With
- **React 18**: For reactive UI components
- **CryptoJS**: For AES-256 encryption
- **Browser localStorage**: For local data persistence
- **Pure CSS**: No frameworks, custom animations

### Browser Compatibility
- ✅ Chrome/Edge (v90+)
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Opera (v76+)

### File Size
- Single HTML file: ~35KB
- Zero external dependencies (all CDN-loaded)
- Works offline after first load

## 🔒 Privacy & Security

### What We DON'T Do
- ❌ No data collection
- ❌ No analytics or tracking
- ❌ No cloud sync
- ❌ No server-side storage
- ❌ No third-party services
- ❌ No advertisements

### What You Control
- ✅ Your master password
- ✅ Your encrypted data (stored locally)
- ✅ Your backups
- ✅ When to lock/unlock
- ✅ What gets stored

## 📱 Quick Access Setup

### Pin as Browser Tab
1. Open `password_manager.html`
2. Right-click the tab → Pin Tab
3. Access instantly with `Ctrl+1` (or `Cmd+1` on Mac)

### Desktop Shortcut
1. Right-click `password_manager.html`
2. Send to → Desktop (create shortcut)
3. Double-click to open instantly

### Bookmark for Quick Access
1. Open the file in your browser
2. Press `Ctrl+D` (or `Cmd+D` on Mac)
3. Save to bookmarks bar
4. One-click access anytime

## 🎨 Customization

Want to modify the colors or style? The entire application is self-contained in one HTML file. Open it in any text editor and modify the CSS in the `<style>` section to match your preferences.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Additional password strength metrics
- More category options
- Biometric authentication support
- Password history tracking
- Duplicate password detection
- Breach checking (offline)
- Dark/light theme toggle
- Mobile-optimized interface

## ⚠️ Important Notes

### Master Password Recovery
**There is NO way to recover your master password.** If you forget it, your encrypted data cannot be decrypted. Make sure to:
- Choose a memorable but strong password
- Consider writing it down and storing it securely
- Don't use a password you use anywhere else

### Data Persistence
Your passwords are stored in browser localStorage. This means:
- ✅ Data persists between sessions
- ⚠️ Clearing browser data will delete your vault
- ⚠️ Each browser has its own separate vault
- ⚠️ Private/Incognito mode data is deleted when closed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with React and CryptoJS
- Inspired by the need for true client-side security
- Designed for bug bounty hunters and security professionals

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Check existing issues for solutions
- Review the documentation above

## 🌟 Star This Project

If you find SecureVault useful, please consider giving it a star! It helps others discover this tool.

---

**Remember**: Your security is in your hands. Use a strong master password, keep regular backups, and never share your master password with anyone.

**Stay Secure! 🔐**
