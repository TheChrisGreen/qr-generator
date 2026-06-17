# QR Code Generator

A lightweight, single-file web app for generating QR codes for various data types. No frameworks, no build step — just open `index.html` in a browser and go.

## Features

- **12 QR Code Types:**
  - Plain Text
  - URL / Web Link
  - Contact (vCard)
  - Phone Number
  - SMS Message
  - Email
  - Wi-Fi Network
  - Calendar Event
  - Geolocation
  - Payment Information (PayPal, Venmo, Cash App, UPI, WeChat, Alipay)
  - App Store Link (iOS / Android)
  - Binary Data (hex-encoded)
- **Instant Preview:** QR code renders client-side using the QRCode.js library.
- **Download as PNG:** One-click save of the generated QR code.
- **Responsive Design:** Works on desktop and mobile.
- **Zero Dependencies:** Single HTML file, no server required.

## Usage

1. Open `index.html` in any modern browser.
2. Select a QR code **type** from the dropdown.
3. Fill in the fields that appear.
4. Click **Generate QR Code**.
5. Download the result as a PNG, or reset to start over.

## Tech Stack

- **HTML / CSS / JavaScript** — vanilla, no frameworks
- **QRCode.js** — client-side QR code generation via CDN

## License

MIT
