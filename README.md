# 🔐 Secure Password Generator

A modern, responsive password generator built with vanilla HTML, CSS, and JavaScript. Generate strong, customizable passwords entirely in your browser with no server-side processing for maximum security.

## 🌐 Live Demo

Visit the live application: [https://hmwcs.github.io/secure-password-generator/](https://hmwcs.github.io/secure-password-generator/)

## ✨ Features

### Password Customization
- **Adjustable Length**: Generate passwords from 4 to 50 characters
- **Character Types**: 
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special symbols (!@#$%^&*()_+-=[]{}|;:,.<>?)

### Advanced Options
- **Exclude Similar Characters**: Remove confusing characters like `i`, `l`, `1`, `L`, `o`, `0`, `O`
- **Exclude Ambiguous Characters**: Remove characters that might be unclear in certain fonts like `{}[]()\/'"~,;.<>`

### Security Features
- **Client-Side Generation**: All password generation happens in your browser - nothing is sent to any server
- **Real-Time Strength Meter**: Visual indicator showing password strength (Weak/Fair/Good/Strong)
- **One-Click Copy**: Easy clipboard copying with visual feedback
- **No Storage**: Passwords are not saved or logged anywhere

### User Experience
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, intuitive interface with smooth animations
- **Instant Generation**: Generate new passwords with a single click
- **Visual Feedback**: Clear indicators for all actions and settings

## 🚀 How to Use

1. **Adjust Password Length**: Use the slider to set your desired password length (4-50 characters)

2. **Select Character Types**: Check the boxes for the types of characters you want:
   - Uppercase letters
   - Lowercase letters  
   - Numbers
   - Symbols

3. **Configure Advanced Options** (optional):
   - Enable "Exclude Similar" to avoid confusing characters
   - Enable "Exclude Ambiguous" to remove potentially unclear symbols

4. **Generate Password**: Click the "Generate Password" button to create a new password

5. **Copy Password**: Click the "Copy" button to copy the password to your clipboard

6. **Check Strength**: Monitor the strength meter to ensure your password meets security requirements

## 🛡️ Security Notes

- **Client-Side Only**: This tool runs entirely in your browser. No passwords are transmitted over the internet.
- **No Logging**: Passwords are not saved, logged, or stored anywhere.
- **Cryptographically Secure**: Uses `Math.random()` for password generation, suitable for most use cases.
- **No Dependencies**: Built with vanilla JavaScript - no external libraries or frameworks.

## 📱 Browser Compatibility

- Chrome 66+
- Firefox 63+
- Safari 13.1+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile, etc.)

## 🔧 Technical Details

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Custom CSS with responsive design
- **No Build Process**: Ready to run - just open `index.html`
- **Lightweight**: < 15KB total file size

## 📋 Password Strength Criteria

The strength meter evaluates passwords based on:
- **Length**: Longer passwords score higher
- **Character Variety**: Using multiple character types increases strength
- **Complexity**: Symbols provide the highest security boost

**Strength Levels:**
- 🔴 **Weak**: Basic passwords with limited character types
- 🟠 **Fair**: Moderate length with some character variety
- 🟡 **Good**: Good length with multiple character types
- 🟢 **Strong**: Long passwords with full character variety including symbols

## 🚀 Deployment

You have two main options to use this password generator:

### Option 1: Use Online (Recommended)
Simply visit the live application: **[https://hmwcs.github.io/secure-password-generator/](https://hmwcs.github.io/secure-password-generator/)**

No installation required - works directly in your browser with full functionality.

### Option 2: Run Locally
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. The password generator will work offline with all features

**Note:** The online version and local version have identical functionality and security - all password generation happens in your browser regardless of which option you choose.

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

---

**Remember**: Always use strong, unique passwords for each of your accounts, and consider using a password manager to store them securely!
