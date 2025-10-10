# Universal Code Generator

A modern, responsive web application that generates both QR codes and barcodes with a clean, user-friendly interface.

## Features

- **Dual Code Generation**: Switch between QR codes and barcodes
- **Instant Generation**: Real-time code generation as you type
- **Download Support**: Download generated codes as PNG (QR) or SVG (Barcode)
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Clean interface built with Tailwind CSS and Inter font
- **Error Handling**: User-friendly error messages and validation

## Default Configuration

- **Default URL**: `https://bio-self-seven.vercel.app/`
- **QR Code Size**: 256x256 pixels
- **Barcode Format**: CODE128
- **Error Correction**: High level for QR codes

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with Tailwind CSS framework
- **JavaScript**: Vanilla JS for functionality
- **External Libraries**:
  - [QRCode.js](https://github.com/davidshimjs/qrcodejs) - QR code generation
  - [JsBarcode](https://github.com/lindell/JsBarcode) - Barcode generation
  - [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
  - [Inter Font](https://fonts.google.com/specimen/Inter) - Typography

## Usage

1. **Select Code Type**: Choose between QR Code or Bar Code using radio buttons
2. **Enter Data**: Input any URL, text, or numbers in the text field
3. **Generate**: Click "Generate Code" or the code updates automatically
4. **Download**: Click "Download Code" to save as PNG (QR) or SVG (Barcode)

## File Structure

```
qr code/
├── index.html          # Main application file
└── README.md          # This documentation
```

## Code Features

### QR Code Generation
- High error correction level
- 256x256 pixel resolution
- Black and white color scheme
- Canvas-based rendering
- PNG download format

### Barcode Generation
- CODE128 format support
- Alphanumeric input validation
- SVG-based rendering
- Automatic text truncation for long inputs
- SVG download format with XML headers

### User Interface
- Responsive design for all screen sizes
- Real-time input validation
- Success/error message system
- Dynamic button text updates
- Clean, modern aesthetic

## Browser Compatibility

- Modern browsers with HTML5 Canvas support
- JavaScript enabled
- SVG support for barcode functionality

## Getting Started

1. Open `index.html` in any modern web browser
2. The application loads with a default QR code for the bio website
3. Switch between code types using the radio buttons
4. Enter your desired text or URL
5. Download the generated code using the download button

## Customization

The application can be easily customized by modifying:
- Default URL in the input field
- Color schemes in the CSS
- Code dimensions and formats
- UI styling with Tailwind classes
