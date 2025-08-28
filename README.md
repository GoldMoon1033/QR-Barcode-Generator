# 🔳 QR Code & Barcode Generator

A modern, responsive web application that generates QR codes and barcodes for URLs, text, WiFi credentials, and downloadable files. Built with vanilla HTML, CSS, and JavaScript for maximum compatibility and performance.

![QR Code Generator Banner](https://via.placeholder.com/800x400/667eea/ffffff?text=QR+%26+Barcode+Generator)

## ✨ Features

### 🎯 Multiple Generation Types
- **🔗 URL Generator** - Create QR codes and barcodes for website links
- **📝 Text Generator** - Generate codes for any text content
- **📶 WiFi Generator** - Share WiFi credentials via QR codes
- **📁 File Generator** - Upload files and create download QR codes

### 🛠️ Technical Features
- ⚡ **Real-time generation** - Codes update instantly as you type
- 📱 **Responsive design** - Perfect on desktop, tablet, and mobile
- 🎨 **Modern UI** - Clean interface with smooth animations
- 📥 **Download options** - Save as PNG or SVG formats
- 📋 **Copy to clipboard** - Quick sharing functionality
- 🖱️ **Drag & drop** - Easy file uploads with visual feedback
- 🔒 **Client-side processing** - Your data never leaves your browser

### 📋 Supported Code Types
- **QR Codes** - High-quality, customizable QR codes
- **Code128 Barcodes** - Industry-standard linear barcodes
- **WiFi QR Codes** - WPA/WPA2, WEP, and open network support

## 🌐 Browser Compatibility

| Browser | Version | Status |
|---------|---------|---------|
| Chrome | 60+ | ✅ Fully Supported |
| Firefox | 60+ | ✅ Fully Supported |
| Safari | 12+ | ✅ Fully Supported |
| Edge | 79+ | ✅ Fully Supported |
| Opera | 47+ | ✅ Fully Supported |
| Mobile Safari | iOS 12+ | ✅ Fully Supported |
| Chrome Mobile | Android 60+ | ✅ Fully Supported |

### Required Browser Features
- Canvas API support
- File API support
- Clipboard API (for copy functionality)
- Drag and Drop API

## 🚀 Getting Started

### Quick Start
1. **Download** or clone this repository
2. **Open** `CodeGenerator.html` in your web browser
3. **Start generating** codes immediately - no installation required!

### Using the Generator

#### 🔗 URL Generator
1. Click on the "🔗 URL" tab
2. Enter your website URL (e.g., `https://example.com`)
3. Choose between QR Code or Barcode
4. Download or copy the generated code

#### 📝 Text Generator
1. Switch to the "📝 Text" tab
2. Type or paste your text content
3. Select your preferred code type
4. Save or share your generated code

#### 📶 WiFi Generator
1. Navigate to the "📶 WiFi" tab
2. Enter your network details:
   - **SSID** (Network name)
   - **Security Type** (WPA/WPA2, WEP, or Open)
   - **Password** (if required)
   - **Hidden Network** (check if applicable)
3. Share the QR code for easy WiFi access

#### 📁 File Generator
1. Go to the "📁 File" tab
2. Upload a file by:
   - Clicking the upload area, or
   - Dragging and dropping a file
3. Generate a QR code containing the file data
4. Share for easy file transfer

## 📁 Project Structure

```
qr-barcode-generator/
│
├── CodeGenerator.html              # Main application file
├── README.md              # Project documentation
└── assets/               # Optional assets folder
    ├── screenshots/      # Application screenshots
    └── icons/           # Favicon and app icons
```

## 🔧 Technologies Used

- **HTML5** - Semantic markup and file handling
- **CSS3** - Modern styling with flexbox/grid and animations
- **Vanilla JavaScript** - Core functionality and DOM manipulation
- **QRCode.js** - QR code generation library
- **JsBarcode** - Barcode generation library

### External Dependencies
```html
<!-- QR Code Library -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcode/1.5.3/qrcode.min.js"></script>

<!-- Barcode Library -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jsbarcode/3.11.5/JsBarcode.all.min.js"></script>
```

## 📱 Mobile Support

The application is fully responsive and optimized for mobile devices:
- Touch-friendly interface
- Optimized layouts for small screens
- Mobile-specific interactions
- Gesture support for file uploads

## 🔒 Privacy & Security

- **Client-side only** - All processing happens in your browser
- **No data transmission** - Your information never leaves your device
- **No cookies** - No tracking or data storage
- **Secure file handling** - Files are processed locally using HTML5 APIs

## 🎨 Customization

### Color Scheme
The application uses a modern gradient color scheme that can be easily customized by modifying the CSS variables:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --secondary-gradient: linear-gradient(135deg, #2c3e50, #3498db);
}
```

### Adding New Code Types
To add support for new barcode formats, extend the JsBarcode configuration:

```javascript
JsBarcode(svg, text, { 
  format: "YOUR_FORMAT", 
  width: 2, 
  height: 100 
});
```

## 📊 Performance

- **Lightweight** - Single HTML file under 50KB
- **Fast loading** - Minimal external dependencies
- **Efficient processing** - Optimized JavaScript algorithms
- **Memory conscious** - Proper cleanup and garbage collection

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Ideas for Contributions
- Support for additional barcode formats
- Bulk generation capabilities
- Custom styling options
- API integration for dynamic content
- Print optimization features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature request? Please open an issue on GitHub with:
- **Clear description** of the issue or feature
- **Steps to reproduce** (for bugs)
- **Expected behavior**
- **Screenshots** (if applicable)
- **Browser and version** information

## 🙏 Acknowledgments

- **QRCode.js** - Excellent QR code generation library
- **JsBarcode** - Comprehensive barcode generation solution
- **Modern CSS** - Inspiration from contemporary web design trends

## 📞 Contact

- **GitHub** - [@yourusername](https://github.com/yourusername)
- **Email** - your.email@example.com
- **Portfolio** - [yourwebsite.com](https://yourwebsite.com)

---

⭐ **Star this repository** if you find it helpful!

![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)
![HTML5](https://img.shields.io/badge/HTML5-Latest-orange.svg)
![CSS3](https://img.shields.io/badge/CSS3-Latest-blue.svg)
![Responsive](https://img.shields.io/badge/Responsive-Yes-green.svg)
