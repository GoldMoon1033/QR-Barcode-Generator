# 🔳 QR Code & Barcode Generator

A modern, responsive web application that generates QR codes and barcodes for URLs, text, WiFi credentials, and downloadable files. Built with vanilla HTML, CSS, and JavaScript for maximum compatibility and performance.

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
└── README.md              # Project documentation
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

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature request? Please open an issue on GitHub with:
- **Clear description** of the issue or feature
- **Steps to reproduce** (for bugs)
- **Expected behavior**
- **Screenshots** (if applicable)
- **Browser and version** information
