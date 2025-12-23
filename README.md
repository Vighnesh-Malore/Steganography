# 🔐 Text Steganography Tool

A simple web-based application that hides secret text messages inside images using LSB (Least Significant Bit) steganography technique.

![Project Banner](https://img.shields.io/badge/Steganography-LSB%20Method-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

---

## 📖 About The Project

This steganography tool allows you to hide secret text messages within images, making them invisible to the naked eye. The hidden text can only be revealed by using the decryption feature of this application.

### 🎯 Key Features

- ✅ **Hide Text in Images** - Embed secret messages into any image
- ✅ **Reveal Hidden Text** - Extract hidden messages from encoded images
- ✅ **LSB Steganography** - Uses Least Significant Bit technique for maximum invisibility
- ✅ **Simple Interface** - Clean, black-themed UI with 3D buttons
- ✅ **No Server Required** - Runs completely in your browser
- ✅ **Privacy First** - All processing happens locally on your device

---

## 🚀 Demo

### Encryption Process:
1. Enter your secret message
2. Upload a cover image
3. Click "HIDE TEXT"
4. Download the encoded image

### Decryption Process:
1. Upload the encoded image
2. Click "REVEAL TEXT"
3. Your secret message appears!

---

## 🛠️ Built With

- **HTML5** - Structure
- **CSS3** - Styling with custom 3D buttons
- **Vanilla JavaScript** - Core functionality
- **Canvas API** - Image manipulation
- **Google Fonts (Poppins)** - Typography

---

## 📂 Project Structure

```
steganography-project/
│
├── index.html           # Home page with navigation
├── encryption.html      # Hide text in images
├── decryption.html      # Reveal hidden text
└── README.md           # Project documentation
```

---

## 🎮 How to Use

### Method 1: Run Locally

1. **Clone the repository:**
```bash
git clone https://github.com/YOUR-USERNAME/text-steganography.git
```

2. **Navigate to project folder:**
```bash
cd text-steganography
```

3. **Open in browser:**
- Simply double-click `index.html`
- OR right-click → Open with → Your browser

### Method 2: Deploy to Web

**Using Netlify (Easiest):**
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the project folder
3. Get instant URL!

**Using GitHub Pages:**
1. Push code to GitHub
2. Go to Settings → Pages
3. Select main branch → Save
4. Access at: `https://YOUR-USERNAME.github.io/REPO-NAME`

---

## 🔬 How It Works

### Encryption (LSB Method):
1. Converts text to binary (8 bits per character)
2. Embeds each bit into the Least Significant Bit of image pixels
3. Adds end marker (11111111) to indicate message end
4. Original image appears unchanged to human eye

### Decryption:
1. Extracts LSB from each pixel
2. Converts binary back to text
3. Stops at end marker
4. Displays hidden message

---

## 💻 Technical Details

### Image Processing:
- Uses HTML5 Canvas API
- Fixed canvas size: 300x300 pixels
- Modifies red channel LSB for data hiding
- PNG format for lossless storage

### Supported Formats:
- **Input:** Any image format (JPG, PNG, etc.)
- **Output:** PNG (lossless compression required)

---

## 📱 Browser Compatibility

Works on all modern browsers:
- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

---

## 🎨 UI Features

- **3D Button Effects** - Satisfying press animations
- **Dark Theme** - Easy on the eyes
- **Responsive Design** - Works on all screen sizes
- **Clean Layout** - Minimal and professional

---

## ⚠️ Important Notes

- Hidden text is **NOT encrypted** - just hidden
- Use PNG format to save encoded images (JPG compression destroys hidden data)
- Image quality affects hiding capacity
- Larger images = more text capacity

---

## 🔮 Future Enhancements

- [ ] Add password protection/encryption
- [ ] Support for larger text messages
- [ ] Multiple encoding methods
- [ ] Drag & drop file upload
- [ ] Mobile app version
- [ ] Batch processing

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Your Name**
- GitHub: [@YOUR-USERNAME](https://github.com/YOUR-USERNAME)
- Email: your.email@example.com

---

## 🙏 Acknowledgments

- Inspired by classic steganography techniques
- 3D button design from modern web UI patterns
- Built as a learning project for web development

---

## 📞 Support

If you have any questions or issues:
- Open an issue on GitHub
- Contact via email
- Check existing issues for solutions

---

## ⭐ Show Your Support

Give a ⭐️ if you like this project!

---

**Made with ❤️ and JavaScript**
