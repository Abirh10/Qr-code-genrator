# 🔳 QR Code Generator

A clean, responsive QR Code Generator built using **HTML, CSS, and JavaScript**. Generate QR codes from any text or URL and download them instantly as a PNG image.

---

## ✨ Features

- ✅ Generate QR codes from any text or URL
- 📏 Choose between multiple QR code sizes
  - 200 × 200
  - 300 × 300
  - 400 × 400
- 💾 Download generated QR codes as PNG images
- ⌨️ Keyboard shortcut support (`Ctrl + Enter` / `Cmd + Enter`)
- 📱 Responsive design for desktop and mobile
- 🎨 Modern dark-themed user interface

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (ES6)
- QRCode.js Library

---

## 📂 Project Structure

```
qr-code-generator/
│
├── index.html        # Application structure
├── styles.css        # Styling and responsive layout
├── script.js         # QR generation logic
└── README.md
```


## 📖 How It Works

1. Enter any text or URL.
2. Select your preferred QR code size.
3. Click **Generate QR Code**.
4. The QR code is created instantly.
5. Click **Download QR Code** to save it as a PNG image.

You can also press:

- **Ctrl + Enter** (Windows/Linux)
- **Cmd + Enter** (macOS)

to generate the QR code.

---

## ⚙️ Implementation Details

The application uses the **QRCode.js** library to generate QR codes dynamically.

Workflow:

1. User enters text.
2. Input is validated.
3. Previous QR code is cleared.
4. A new QR code is generated using the selected dimensions.
5. The generated canvas is converted into a PNG Data URL.
6. Clicking the download button automatically downloads the image.

---

## 📚 External Library

This project uses:

**QRCode.js**

https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js

---

## 🎯 Future Improvements

- 🎨 Custom foreground/background colors
- 🖼️ Logo embedding inside QR codes
- 📁 Support for SVG downloads
- 📈 Error correction level selection
- 📜 QR generation history
- 🌙 Light/Dark mode toggle
- 📋 Copy QR image to clipboard
- 📷 Generate QR codes from uploaded files

---



---

### ⭐ If you found this project useful, consider giving it a star!
