# Dummy HTML Website

A simple HTML website with basic content served using Python's built-in HTTP server.

## Project Structure

```
dummy-wp/
├── index.html      # Main HTML file with sample content
└── README.md       # This file
```

## Features

The `index.html` file includes:
- **HTML5 document structure** with proper semantic markup
- **CSS styling** for a clean, responsive design
- **Sample content** including:
  - Headers and paragraphs
  - Unordered and ordered lists
  - Data table with styling
  - Interactive JavaScript alert
  - Highlighted text elements
- **Responsive design** with mobile viewport meta tag
- **Console logging** for debugging

## Getting Started

### Prerequisites
- Python 3.x installed on your system

### Running the Server

1. Navigate to the project directory:
   ```bash
   cd dummy-wp
   ```

2. Start the Python HTTP server:
   ```bash
   python -m http.server 8000
   ```

3. Open your browser and navigate to:
   - http://localhost:8000
   - http://127.0.0.1:8000

### Stopping the Server

To stop the server, press `Ctrl+C` in the terminal where the server is running.

## Usage

- The server will serve the `index.html` file as the default page
- You can modify the HTML file and refresh the browser to see changes
- The server runs on port 8000 by default (you can change this by specifying a different port number)

## Customization

Feel free to modify the `index.html` file to:
- Add more content sections
- Update the styling in the `<style>` tag
- Add more interactive JavaScript features
- Include additional HTML pages

## Alternative Server Options

If you don't have Python installed, you can use other simple HTTP servers:

### Node.js (if you have npm):
```bash
npx serve .
```

### PHP (if you have PHP installed):
```bash
php -S localhost:8000
```

### Live Server (VS Code Extension)
Install the "Live Server" extension in VS Code and right-click on `index.html` → "Open with Live Server"

## Browser Compatibility

This HTML file uses standard HTML5, CSS3, and ES5 JavaScript features that are compatible with all modern browsers.

---

**Created:** September 19, 2025  
**Server:** Python HTTP Server  
**Port:** 8000 (default)