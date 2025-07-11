# SecureChat - Anonymous Encrypted Chat

![SecureChat Logo](https://img.shields.io/badge/SecureChat-Anonymous%20%26%20Encrypted-6366f1?style=for-the-badge&logo=shield&logoColor=white)

A modern, anonymous, and secure chat application that allows users to create and join encrypted chat rooms without any registration. Built with vanilla HTML, CSS, and JavaScript for maximum compatibility and minimal dependencies.

## ✨ Features

### 🔒 **End-to-End Encryption**
- All messages are encrypted before leaving your device
- Only room members can decrypt and read messages
- No server-side message storage

### 👤 **Complete Anonymity**
- No accounts, email, or phone numbers required
- Choose any nickname and start chatting instantly
- No personal data collection

### 🔥 **Ephemeral Messages**
- Messages are never stored on servers
- When you leave a room, your messages disappear forever
- True privacy by design

### 🎨 **Modern UI/UX**
- Beautiful dark theme with gradient accents
- Responsive design for all devices
- Smooth animations and transitions
- Animated particle background

### 🚀 **Easy to Use**
- Create rooms with a simple 5-digit code
- Join rooms instantly with the code
- Copy and share room codes easily
- Real-time messaging interface

## 🖥️ Screenshots

### Welcome Screen
The landing page features a modern design with animated particles and clear call-to-action buttons.

### Chat Interface
Clean, modern chat interface with message encryption indicators and room management tools.

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or dependencies required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/securechat.git
   cd securechat
   ```

2. **Open the application**
   - Simply open `index.html` in your web browser
   - Or serve it using a local web server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Start chatting**
   - Create a new room or join an existing one
   - Share the 5-digit room code with others
   - Start secure, anonymous conversations

## 📱 Usage

### Creating a Room
1. Click "Create Room" on the welcome screen
2. Enter a room name and your nickname
3. Click "Create Room" and wait for the unique 5-digit code
4. Share the code with people you want to invite
5. Click "Enter Room" to start chatting

### Joining a Room
1. Click "Join Room" on the welcome screen
2. Enter the 5-digit room code you received
3. Choose your nickname for the session
4. Click "Join Room" to enter the chat

### Chat Features
- **Send Messages**: Type your message and press Enter or click the send button
- **Copy Room Code**: Click the "Copy Code" button to share with others
- **Leave Room**: Click "Leave" to exit the current room
- **Auto-resize**: Message input automatically resizes as you type

## 🛠️ Technical Details

### Built With
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **Vanilla JavaScript** - No frameworks or libraries required
- **Font Awesome** - Icons for better UX
- **Google Fonts** - Inter font family for modern typography

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Key Features Implementation
- **Responsive Design**: CSS Grid and Flexbox for all screen sizes
- **Animations**: CSS keyframes for smooth transitions
- **Modal System**: Custom modal implementation with backdrop blur
- **Particle Animation**: Dynamic background particles
- **Auto-resize Textarea**: Smart input field that grows with content
- **Copy to Clipboard**: Modern Clipboard API integration

## 🎨 Customization

### Color Scheme
The application uses CSS custom properties for easy theming:

```css
:root {
    --primary-color: #6366f1;
    --primary-hover: #5855eb;
    --secondary-color: #8b5cf6;
    --background-dark: #0f0f23;
    --background-card: #1a1a2e;
    /* ... more variables */
}
```

### Modifying Styles
1. Edit the CSS variables in the `<style>` section
2. Customize animations by modifying `@keyframes` rules
3. Adjust responsive breakpoints in media queries

### Adding Features
The modular JavaScript structure makes it easy to add new features:
- Message encryption/decryption
- File sharing
- Voice messages
- User presence indicators

## 🔧 Development

### Project Structure
```
securechat/
├── index.html          # Main application file
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

### Code Organization
- **HTML Structure**: Semantic markup with clear sections
- **CSS Styling**: Organized with logical groupings and comments
- **JavaScript Logic**: Modular functions for different features

### Adding New Features
1. **HTML**: Add new elements in the appropriate sections
2. **CSS**: Add styles following the existing naming conventions
3. **JavaScript**: Create new functions following the modular pattern

## 🚀 Deployment

### Static Hosting
Deploy to any static hosting service:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the files or connect your repository
- **Vercel**: Import your project and deploy instantly
- **Firebase Hosting**: Use Firebase CLI to deploy

### Example Deployment Commands

**Netlify CLI:**
```bash
npm install -g netlify-cli
netlify deploy --prod --dir .
```

**Firebase:**
```bash
npm install -g firebase-tools
firebase init hosting
firebase deploy
```

## 🔒 Security Considerations

### Current Implementation
- Client-side only (no server communication)
- Room codes are generated locally
- Messages are stored only in browser memory

### Production Recommendations
For a production deployment, consider implementing:
- Real WebSocket server for live messaging
- Actual end-to-end encryption (WebCrypto API)
- Rate limiting and spam protection
- Message persistence options
- User authentication (optional)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow the existing code style
- Add comments for complex functionality
- Test on multiple browsers
- Ensure responsive design works
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Font Awesome** for the beautiful icons
- **Google Fonts** for the Inter font family
- **CSS Tricks** for responsive design inspiration
- **MDN Web Docs** for web API references

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/yourusername/securechat/issues) page
2. Create a new issue with detailed information
3. Include browser version and steps to reproduce

## 🗺️ Roadmap

### Planned Features
- [ ] Real-time WebSocket integration
- [ ] Actual end-to-end encryption
- [ ] File sharing capabilities
- [ ] Voice message support
- [ ] Dark/Light theme toggle
- [ ] Message reactions
- [ ] User presence indicators
- [ ] Room persistence options
- [ ] Mobile app versions

### Version History
- **v1.0.0** - Initial release with basic chat functionality
- **v1.1.0** - Added responsive design and animations
- **v1.2.0** - Improved UI/UX and added particle effects

---

<div align="center">

**Made with ❤️ for privacy and security**

[Report Bug](https://github.com/yourusername/securechat/issues) · [Request Feature](https://github.com/yourusername/securechat/issues) · [Documentation](https://github.com/yourusername/securechat/wiki)

</div>