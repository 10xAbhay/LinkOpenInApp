# LinkOpenInApp

A lightweight web application that converts standard YouTube URLs into deep links, allowing videos to open directly in the YouTube app when installed. If the app isn't available, the link automatically falls back to the browser.

## Overview

LinkOpenInApp eliminates the extra app picker dialog by generating a shareable redirect link that intelligently launches the YouTube app on mobile devices while maintaining compatibility across platforms.

## Features

- Generate deep links from standard YouTube URLs
- Directly opens the YouTube app on Android and iOS
- Automatic browser fallback when the app is unavailable
- Supports multiple YouTube URL formats
- Copy generated links with one click
- Responsive, minimal interface
- Fast and lightweight with zero dependencies

## Supported URL Formats

- `https://www.youtube.com/watch?v=VIDEO_ID`
- `https://youtube.com/watch?v=VIDEO_ID`
- `https://m.youtube.com/watch?v=VIDEO_ID`
- `https://youtu.be/VIDEO_ID`
- `https://youtube.com/shorts/VIDEO_ID`
- `https://youtube.com/live/VIDEO_ID`
- `https://youtube.com/embed/VIDEO_ID`

## How It Works

1. Paste a YouTube URL.
2. Click **Generate**.
3. Copy the generated redirect link.
4. Share or open the generated link.
5. The application detects the user's platform and:
   - Launches the YouTube app when installed.
   - Falls back to the browser if the app cannot be opened.

## Platform Support

| Platform | Support |
|----------|---------|
| Android | Intent-based deep linking |
| iOS | `youtube://` URL scheme |
| Desktop | Opens YouTube in the browser |

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript

## Browser Compatibility

- Chrome
- Edge
- Safari
- Firefox
- Mobile Browsers
- In-app browsers (Instagram, Facebook, etc.)

## Getting Started

Clone the repository:

```bash
git clone https://github.com/yourusername/linkopeninapp.git
```

Navigate to the project:

```bash
cd linkopeninapp
```

Run locally:

```bash
# Option 1
Open index.html in your browser

# Option 2
Serve with any static server
```

## Project Structure

```
LinkOpenInApp/
│
├── index.html
├── README.md
└── LICENSE
```

## Roadmap

- Support for additional video platforms
- QR Code generation
- Custom branded redirect links
- Link analytics
- Progressive Web App (PWA)
- API for developers

## Contributing

Contributions are welcome. Please open an issue to discuss significant changes before submitting a pull request.

## License

This project is licensed under the MIT License.

---

Built with simplicity and performance in mind.
