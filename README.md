# WhatsApp Link Generator PWA

A Progressive Web App (PWA) for generating WhatsApp chat links with pre-filled messages.

## Features

- 📱 **Progressive Web App** - Install on any device
- 🔗 **Instant Link Generation** - Create WhatsApp links quickly
- 📝 **Pre-filled Messages** - Add custom messages to links
- 📋 **Copy to Clipboard** - Easy link copying
- 🌐 **Offline Support** - Works without internet connection
- 📱 **Mobile Optimized** - Great experience on all devices

## Installation

### As a PWA (Progressive Web App)

1. **Chrome/Edge**: Click the install button in the address bar
2. **Safari (iOS)**: Tap Share → Add to Home Screen
3. **Firefox**: Click the menu button → Install

### Manual Installation

1. Clone this repository
2. Serve the files using any web server
3. Access via browser

## Usage

1. Enter a phone number (with country code, no + or spaces)
2. Optionally add a pre-filled message
3. Click "Generate Link"
4. Copy the generated WhatsApp link

## PWA Features

- **Offline Support**: Works without internet connection
- **App-like Experience**: Full-screen, no browser UI
- **Fast Loading**: Cached resources for quick access
- **Cross-Platform**: Works on desktop, mobile, and tablet

## Technical Details

- **Service Worker**: Provides offline functionality
- **Web App Manifest**: Defines app appearance and behavior
- **Responsive Design**: Optimized for all screen sizes
- **HTTPS Required**: PWA features require secure connection

## Browser Support

- Chrome 68+
- Firefox 63+
- Safari 11.1+
- Edge 79+

## Development

To test PWA features locally, you'll need to serve the files over HTTPS or use localhost.

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

## Files Structure

```
├── index.html          # Main application
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── icons/             # App icons
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md          # This file
```
