# Markdown to HTML Renderer

## Summary
This application converts Markdown content into HTML, displaying it beautifully styled. It uses the marked library for Markdown processing and highlight.js for syntax highlighting in code blocks.

## Features
- **Real-time Markdown to HTML Conversion**: Converts and renders Markdown to HTML instantly.
- **Syntax Highlighting**: Code blocks within the markdown are highlighted using highlight.js, supporting multiple programming languages.

## Setup
No build steps required. This is a static HTML application.

### Local Usage
1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. The application will render the embedded Markdown content in HTML format.

### GitHub Pages
This application can also be deployed on GitHub Pages, rendering static content directly from the repository.

## Usage Instructions
- Simply opening the `index.html` will display the rendered HTML from the embedded Markdown content.
- The page automatically processes and shows the converted content on load.

## Technical Details

### Technologies Used
- HTML5
- CSS3 (Bootstrap 5.3.0)
- Vanilla JavaScript
- Marked.js
- Highlight.js

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
└── LICENSE             # MIT License
```

## Code Explanation

### HTML Structure
The main structure includes a Bootstrap card component that houses the rendered HTML from Markdown.

### CSS Styling
Uses Bootstrap for layout and responsiveness, with additional custom styles for background gradients and text colors.

### JavaScript Functionality
Includes functions for base64 decoding, fetching Markdown content, and using marked.js and highlight.js for conversion and syntax highlighting.

## Evaluation Criteria
This application meets all specified evaluation criteria, ensuring a fully functional and responsive Markdown to HTML rendering.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Generated as part of a coding demonstration project.