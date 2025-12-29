# Frequently Asked Questions (FAQ)

## General Questions

### What is SecureVault?
SecureVault is a completely client-side password manager that runs entirely in your browser. No servers, no cloud sync, no tracking - just you and your encrypted passwords.

### Is it really secure?
Yes! SecureVault uses AES-256 encryption (military-grade) to protect your passwords. Your data never leaves your device and is encrypted using your master password.

### How much does it cost?
It's completely free and open source! No subscriptions, no premium features, no hidden costs.

### Do I need to install anything?
Nope! Just download the HTML file and open it in any modern browser. No installation, no dependencies, no setup.

## Security Questions

### What happens if I forget my master password?
Unfortunately, there's no way to recover it. The encryption is designed so that without your master password, the data cannot be decrypted. This is a security feature, not a bug!

**Best practices:**
- Choose a memorable password
- Write it down and store it securely offline
- Don't use a password you use elsewhere

### Can you see my passwords?
No! Everything runs locally in your browser. There's no server, no database, and no way for anyone (including the developer) to see your data.

### What if someone gets access to my computer?
If someone has physical access to your computer and your vault is unlocked, they could access your passwords. Always lock your vault (🔒 button) when stepping away.

### Is my data backed up automatically?
No. SecureVault doesn't sync to the cloud. You need to manually export backups using the "Export Vault" button. This is a privacy feature!

### Where are my passwords stored?
In your browser's localStorage. This is a secure, local storage area that's isolated per website/file and persists between sessions.

## Usage Questions

### Can I use this on multiple devices?
Yes, but you'll need to manually sync by exporting from one device and importing to another. Each browser on each device has its own separate vault.

### Can I use this on my phone?
Yes! Open the HTML file in your mobile browser. It works on iPhone Safari, Android Chrome, and other mobile browsers.

### Does it work offline?
Yes! After the first load (which pulls React and CryptoJS from CDN), it works completely offline.

### Can I share passwords with others?
You can export specific passwords and share the JSON, but this isn't recommended. Each person should have their own vault.

### How do I backup my vault?
Click "Export Vault" in the sidebar. This downloads a JSON file with all your passwords. Store this file securely (consider encrypting it with another tool).

## Technical Questions

### What browsers are supported?
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+
- Most modern browsers with localStorage support

### Can I self-host this?
Sure! You can put it on any web server, but keep in mind:
- It doesn't need a server to function
- Hosting it doesn't add security (it's client-side)
- Each user still stores data locally

### Can I modify the code?
Absolutely! It's open source under MIT license. The entire app is in one HTML file, so it's easy to customize.

### What about browser extensions?
Malicious browser extensions could potentially access your vault when it's unlocked. Use extensions from trusted sources only.

### What encryption does it use?
- **Encryption**: AES-256 (Advanced Encryption Standard)
- **Hashing**: SHA-256 for master password
- **Library**: CryptoJS (well-tested, industry standard)

## Privacy Questions

### Do you collect any data?
No. Zero. Nada. There's no analytics, no tracking, no telemetry, no servers.

### Do you use cookies?
No cookies are used. Only localStorage for your encrypted vault data.

### Can anyone see what passwords I have?
Not unless they:
1. Have physical access to your unlocked vault, OR
2. Have your master password AND access to your browser's data

### Is this GDPR compliant?
Yes, because there's no data collection, processing, or transmission. Your data never leaves your device.

## Comparison Questions

### How is this different from LastPass/1Password/Bitwarden?
**Pros:**
- ✅ Completely free
- ✅ No account needed
- ✅ No cloud sync (privacy)
- ✅ Open source
- ✅ No installation
- ✅ Works offline

**Cons:**
- ❌ No automatic cloud sync
- ❌ No mobile apps
- ❌ No browser extensions
- ❌ Manual backup needed
- ❌ No team features
- ❌ No password sharing

### Should I switch from my current password manager?
That depends on your needs:
- Need cloud sync? Stick with your current manager
- Want maximum privacy? SecureVault might be better
- Want offline-only? SecureVault is perfect
- Want convenience? Commercial options might be easier

## Troubleshooting

### My passwords disappeared!
Common causes:
- Cleared browser data? (includes localStorage)
- Using private/incognito mode? (data deleted when closed)
- Different browser? (each browser has separate storage)
- **Solution**: Restore from your backup export

### I can't unlock my vault
- Double-check your master password (case-sensitive)
- Try refreshing the page
- If you truly forgot it, there's no recovery option

### The page won't load
- Check your internet connection (needed for first load)
- Try a different browser
- Check browser console for errors (F12)
- Ensure JavaScript is enabled

### Import isn't working
- Make sure the file is valid JSON
- Check that it's not corrupted
- Try opening the JSON in a text editor first

### Export button does nothing
- Check if downloads are blocked in your browser
- Try a different browser
- Check browser permissions for downloads

## Best Practices

### Password Security
- Use 16+ character master password
- Enable password generator for new passwords
- Use different passwords for each account
- Review password strength indicators
- Update weak passwords regularly

### Vault Management
- Export backups weekly (or after major changes)
- Store backups in multiple secure locations
- Lock vault when stepping away
- Don't use on public computers
- Keep your browser updated

### Organization
- Use categories effectively
- Add notes for recovery questions
- Include URLs for quick access
- Use descriptive titles
- Keep related accounts together

## Still Have Questions?

- Check the [README.md](README.md) for more details
- Review [SECURITY.md](SECURITY.md) for security info
- Open an issue on GitHub
- Read the source code (it's all in one file!)

---

**Remember: Your security is your responsibility. Use strong passwords and keep backups! 🔒**
