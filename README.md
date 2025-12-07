# QR Code Generator

A simple, clean, and user-friendly web application for generating QR codes from text or URLs. Built with vanilla JavaScript, HTML, and CSS.

## Features

- 🎯 **Simple Interface**: Clean and intuitive user interface
- ⚡ **Fast Generation**: Quick QR code generation using external API
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
- 🔄 **Loading States**: Visual feedback with loading spinner during generation
- ✨ **No Dependencies**: Pure vanilla JavaScript - no frameworks required

## How It Works

1. Enter any text or URL in the input field
2. Click the "Generate QR code" button
3. Your QR code will be displayed instantly

## Project Structure

```
QR-GENERATOR/
├── index.html          # Main HTML file
├── style.css           # Styling and layout
├── js/
│   ├── main.js         # Main application logic
│   ├── qrGenerator.js  # QR code generation module
│   └── ui.js           # UI handling module
└── README.md           # Project documentation
```

## Technologies Used

- **HTML5**: Structure and markup
- **CSS3**: Styling and animations
- **Vanilla JavaScript (ES6)**: Application logic with modules
- **QR Server API**: External API for QR code generation

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/QR-GENERATOR.git
   cd QR-GENERATOR
   ```

2. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## Usage

Simply enter any text or URL in the input field and click the "Generate QR code" button. The generated QR code will appear below the input field. You can right-click on the QR code image to save it.

## API

This project uses the [QR Server API](https://goqr.me/api/) for generating QR codes:
- API Endpoint: `https://api.qrserver.com/v1/create-qr-code/`
- Default size: 300x300 pixels
- Format: PNG image

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Author

Created with ❤️ for easy QR code generation

---

**Note**: This application uses an external API service. Make sure you have an active internet connection to generate QR codes.

