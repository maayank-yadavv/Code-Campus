# 🔐 CODE TANTRA SOLUTIONS - Secure Educational Portal

A modern, React-based educational portal with authentication, lecture management, and AI-powered assistance. Built for secure access to educational content with an intuitive interface.

**🌐 [Live Site](https://codetantrasolution.netlify.app)**

> **📌 Note:** The source code is not publicly displayed due to personal reasons. However, you can explore the live application to see the features in action.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 🌟 Features

### 🔒 **Authentication System**
- Secure login with email/password
- Google OAuth integration
- Password visibility toggle
- Session management
- Protected routes

### 📚 **Lecture Management**
- Browse lecture catalog with visual cards
- Image-based lecture materials (PNG format)
- Fullscreen image viewer with zoom controls
- Navigation between images (previous/next)
- Lecture progress tracking
- Organized by lecture numbers (1-29+)

### 🤖 **AI Assistant Integration**
- Powered by Google Generative AI
- Context-aware responses
- Markdown formatting support
- Real-time chat interface
- Copy responses to clipboard

### 🎨 **Modern UI/UX**
- Dark theme with gradient accents
- Responsive design (mobile-first)
- Smooth animations and transitions
- Accessibility features (keyboard navigation, focus states)
- Touch-optimized for mobile devices

### 🖼️ **Image Gallery Features**
- Support for 350+ lecture images
- Zoom in/out controls
- Fullscreen viewing mode
- Image preloading for smooth navigation
- High-resolution PNG support

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools required - runs directly in browser!

### Installation

1. **Clone or Download**
   ```bash
   git clone https://github.com/maayank-yadavv/mayank.git
   cd mayank
   ```

2. **File Structure**
   ```
   mayank/
   ├── assets/
   │   └── images/
   │       ├── 101.png - 116.png   # Lecture 1 images
   │       ├── 201.png - 223.png   # Lecture 2 images
   │       ├── 301.png - 326.png   # Lecture 3 images
   │       └── ... (more lecture images)
   ├── index.html                  # Main application file
   ├── styles.css                  # Custom styles
   ├── .gitattributes              # Git LFS configuration
   └── README.md
   ```

3. **Launch Application**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Python
     python -m http.server 8000
     
     # Node.js
     npx serve
     ```

4. **Access Portal**
   - Navigate to `http://localhost:8000` (if using server)
   - Or directly open the HTML file

## 🎯 Usage Guide

### Login
1. Enter your email and password
2. Or click "Continue with Google" for OAuth login
3. Click "Access Secure Portal" to proceed

### Viewing Lectures
1. Browse available lectures from the catalog
2. Click on any lecture card to open
3. Navigate through images using arrow buttons
4. Use zoom controls for better viewing
5. Toggle fullscreen mode for immersive experience

### Using AI Assistant
1. Click the AI chat icon in the navigation
2. Type your question or request
3. AI will provide contextual responses
4. Copy responses using the copy button

### Adding New Lectures

To add images to a lecture, edit the `MANUAL_IMAGE_CONFIG` object in `index.html`:

```javascript
const MANUAL_IMAGE_CONFIG = {
    1: ["assets/images/101.png", "assets/images/102.png", ...],  // Lecture 1 images
    2: ["assets/images/201.png", "assets/images/202.png", ...],  // Lecture 2 images
    // Add your new lecture
    30: ["assets/images/3001.png", "assets/images/3002.png", ...],
};
```

Then place the corresponding image files in `assets/images/`.

## 📸 Image Organization

Images are organized by lecture number inside `assets/images/`:
- **Format**: `assets/images/[LectureNumber][ImageNumber].png`
- **Example**: 
  - Lecture 1: assets/images/101.png, assets/images/102.png, assets/images/103.png, etc.
  - Lecture 10: assets/images/1001.png, assets/images/1002.png, assets/images/1003.png, etc.
  - Lecture 22: assets/images/2201.png, assets/images/2202.png, assets/images/2203.png, etc.

## 🛠️ Technology Stack

### Frontend
- **React 18**: UI components and state management
- **Babel Standalone**: JSX compilation in browser
- **Tailwind CSS**: Utility-first styling
- **Marked.js**: Markdown parsing for AI responses

### Libraries & APIs
- **Google Generative AI**: AI-powered assistance
- **Google OAuth**: Authentication
- **Custom Icons**: Inline SVG components

### Features
- **No build process required**: Runs directly in browser
- **CDN-based dependencies**: Fast loading
- **Progressive enhancement**: Works without JavaScript for basic content

## 🎨 Customization

### Colors & Theme
Edit the CSS variables in `index.html` or `styles.css`:
```css
:root {
    --primary-color: #3b82f6;
    --secondary-color: #8b5cf6;
    --background: #0f172a;
}
```

### Layout
Modify Tailwind classes in the React components within `index.html`.

### Images
Update image paths in `MANUAL_IMAGE_CONFIG` to use your own content.

## 📱 Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔐 Security Features

- Client-side authentication
- Secure session management
- Protected content access
- Input validation
- XSS protection through React

## 📊 Current Content

- **Total Lectures**: 29+
- **Total Images**: 350+
- **Categories Covered**: Various educational topics
- **Image Format**: PNG (high quality)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Mayank Yadav**
- GitHub: [@maayank-yadavv](https://github.com/maayank-yadavv)
- LinkedIn: [Connect with me](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- React team for the amazing framework
- Tailwind CSS for the utility-first CSS framework
- Google for Generative AI API
- Open source community

## 📞 Support

For support, issues, or questions:
- Open an issue on GitHub
- Contact: [101mayankyadav@gmail.com]

## 🔄 Updates & Roadmap

### Current Version: 1.0.0

### Planned Features:
- [ ] Backend integration for data persistence
- [ ] User progress tracking
- [ ] Video lecture support
- [ ] Quiz and assessment module
- [ ] Dark/Light theme toggle
- [ ] Multi-language support
- [ ] Offline mode with PWA
- [ ] Export notes functionality

## 📚 Documentation

For detailed documentation, visit:
- [User Guide](docs/USER_GUIDE.md)
- [Developer Guide](docs/DEVELOPER_GUIDE.md)
- [API Reference](docs/API_REFERENCE.md)

---

**Made with ❤️ for education**

*Last Updated: December 2025*
