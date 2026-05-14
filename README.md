# MaterialHub - Industrial Materials & Products

A modern, responsive website for showcasing industrial materials and products. Built with HTML, CSS, and vanilla JavaScript with dynamic component loading.

## Project Structure

```
.
├── index.html              # Main entry point
├── navbar.html             # Navigation bar component
├── products.html           # Products section component
├── installation.html       # Installation section component
├── pricing.html            # Pricing section component
├── features.html           # Features section component
├── footer.html             # Footer component
├── script.js               # JavaScript for dynamic component loading
├── style.css               # Styling for all components
└── README.md               # This file
```

## Features

- **Dynamic Component Loading**: All major sections are loaded dynamically using the Fetch API
- **Responsive Design**: Mobile-friendly and works on all device sizes
- **Smooth Scrolling**: Smooth navigation between sections
- **Modular Architecture**: Each section is a separate HTML component

## Setup Instructions

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Python 3 (for running local server) OR Node.js (alternative option)

### Installation

1. Clone or download this project
2. Navigate to the project directory:
   ```bash
   cd path/to/web_work
   ```

## Running the Project

### Option 1: Using Python (Recommended)

**Python 3.x:**
```bash
python -m http.server 8000
```

**Python 2.x:**
```bash
python -m SimpleHTTPServer 8000
```

Then open your browser and navigate to:
```
http://localhost:8000
```

### Option 2: Using Node.js

If you have Node.js installed, you can use `http-server`:

```bash
npx http-server
```

This will start a server and display the URL in your terminal (usually `http://localhost:8080`).

### Option 3: Using VS Code Live Server Extension

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Important Note

⚠️ **Do NOT open `index.html` directly with `file://` protocol** in your browser, as the Fetch API will be blocked by browser security policies. Always use a local web server (http:// or https://).

## Project Components

### Navbar
Located in `navbar.html` - Contains the main navigation menu with links to all major sections.

### Products Section
Located in `products.html` - Displays available products and their details.

### Installation Section
Located in `installation.html` - Installation guide and instructions for products.

### Pricing Section
Located in `pricing.html` - Pricing information and plans.

### Features Section
Located in `features.html` - Key features and benefits of the materials.

### Footer
Located in `footer.html` - Footer information and additional links.

## Development

The website uses a modular architecture where:
- `script.js` handles dynamic component loading via the Fetch API
- `style.css` contains all styling for the website
- Each HTML file (except `index.html`) represents a reusable component

### Modifying Components

To edit any component:
1. Open the corresponding HTML file (e.g., `navbar.html`, `products.html`)
2. Make your changes
3. Refresh the browser to see updates

### Adding Styling

All CSS is centralized in `style.css`. Add or modify styles there.

## Troubleshooting

### "Error loading component" message

**Problem**: The navbar or other components show an "Error loading component" message.

**Solution**: Ensure you're running the project through a local web server, not by opening the HTML file directly. Follow the "Running the Project" section above.

### Components not loading

1. Check the browser console (F12) for error messages
2. Verify all `.html` files are in the same directory
3. Ensure your server is running and accessible

## Browser Compatibility

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Internet Explorer: ❌ Not supported (uses modern JavaScript features)

## License

This project is created for MaterialHub.

## Contact

For issues or questions, please refer to the contact section on the website.
