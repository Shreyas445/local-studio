# 🛠️ Web Tools Studio

A collection of powerful, fast, and completely private web utilities that run **entirely in your browser**. No backend servers, no data uploads, and absolute privacy. 

Built with modern HTML, CSS, and Vanilla JavaScript, these tools leverage cutting-edge client-side libraries (like TensorFlow/MediaPipe and Tesseract.js) to deliver premium features for free.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## ✨ Live Demo
*(Optional: If you host this on GitHub Pages, put your link here! e.g., [Try it out here](https://yourusername.github.io/web-tools-studio))*

---

## 🧰 The Toolkit

### 1. 🪄 Background Remover Studio (`bgremover.html`)
An advanced image masking and background removal tool.
* **AI Auto-Removal:** Uses Google's MediaPipe Machine Learning to instantly isolate human subjects.
* **Chroma Key:** Select up to 5 background colors to key out (Green Screen removal).
* **Manual Brush & Magic Wand:** Erase, restore, or magic-erase connected colors. Includes a mobile-friendly "Magnifier Loupe" for precise finger-painting.
* **Live Feathering:** Non-destructive edge smoothing.

### 2. 📄 Image to PDF Studio (`imagetopdf.html`)
Combine multiple images into a single PDF document.
* **True Searchable OCR:** Extracts text from your images and lays it *invisibly* over the PDF, allowing you to `Ctrl+F` and highlight text directly on the image!
* **Drag & Drop:** Reorder pages effortlessly.
* **Smart Sizing:** Export as A4, Letter, or "Match Image Size" for zero white borders.

### 3. 🖼️ PDF to Image Extractor (`pdftoimage.html`)
Extract high-resolution images from any PDF document.
* Generates a preview grid of all PDF pages.
* Select specific pages to export as PNG or JPG.
* Automatically zips files if multiple pages are selected to prevent browser popup blocks.

### 4. 📝 Smart Text Extractor (`textextractor.html`)
On-device Optical Character Recognition (OCR).
* Upload or paste an image, then click and drag a box over the text you want to read.
* Uses Tesseract.js to mathematically locate and extract text in seconds.
* Automatically enhances messy/stylish fonts for better reading accuracy.

### 5. ✂️ Smart Image Resizer (`imageresizer.html`)
Crop, resize, and compress images.
* Integrated `Cropper.js` for precise aspect-ratio cropping (1:1, 16:9, etc.).
* Force exact pixel dimensions while locking/unlocking aspect ratios.
* Adjust compression quality to drastically reduce file size (KB/MB).

### 6. 🎨 QR Code Generator (`QRgenerator.html`)
Design custom QR codes for Links, WiFi, Maps, and Emails.
* Add center logos (instant load SVG presets like WiFi, GitHub, YouTube, or custom uploads).
* Customize foreground/background colors and apply gradients.
* Adjust dot and corner styling (Rounded, Classy, Square).

### 7. 🔍 QR Code Reader (`QRreader.html`)
Instantly scan and decode QR codes. *(Note: Ensure this file is present in your repo!)*

---

## 🚀 Getting Started

Since these tools have **zero backend dependencies**, installation is instant.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/web-tools-studio.git](https://github.com/yourusername/web-tools-studio.git)
