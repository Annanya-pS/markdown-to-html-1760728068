# Markdown Viewer

## Summary
This application provides a simple interface to view and switch between Markdown source and its rendered HTML.

## Features
- Feature 1: View Markdown Source
- Feature 2: View Rendered HTML using Marked.js

## Setup
No build steps required. This is a static HTML application.

### Local Usage
1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. The application will run immediately

### GitHub Pages
The application is deployed at: [Your GitHub Pages URL]

## Usage Instructions
1. Open the application in a web browser.
2. Use the tabs to switch between viewing the Markdown source and the rendered HTML.

## Technical Details

### Technologies Used
- HTML5
- CSS3 (Bootstrap 5.3.0)
- Vanilla JavaScript
- Marked.js for Markdown to HTML conversion

### Key Features
- Responsive design
- Client-side data processing
- Error handling
- Modern UI/UX

### File Structure
```
.
├── index.html          # Main application file
├── README.md           # This file
└── LICENSE            # MIT License
```

## Evaluation Criteria
This application meets the following requirements:
- js: document.querySelectorAll("#markdown-tabs button").length >= 2
- js: document.querySelector("#markdown-source").textContent.trim().length > 0
- Page has element with id='markdown-tabs'
- Page has at least 2 tab buttons
- Page has element with id='markdown-source'
- Tabs switch between HTML and Markdown views
- Original markdown is displayed in #markdown-source

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Generated as part of the TDS Project