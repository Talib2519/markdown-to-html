# Markdown Viewer Application

This is a single-file, responsive web application designed to render Markdown content (specifically `input.md`) directly into HTML using the `marked.js` library and styled with Tailwind CSS.

## Features

*   **Single-File Application**: All code is contained within `index.html` for easy deployment and sharing.
*   **Responsive Design**: Utilizes Tailwind CSS to ensure a great user experience across various device sizes.
*   **Markdown to HTML Conversion**: Automatically fetches `input.md` and converts its content into readable HTML.
*   **Dynamic Loading**: Markdown content is loaded asynchronously using JavaScript.

## Usage

1.  **Save Files**: Ensure `index.html` and `input.md` are in the same directory.
2.  **Open `index.html`**: Simply open `index.html` in your web browser.

The application will automatically fetch `input.md` and display its rendered HTML content. If `input.md` is not found or there's an issue fetching it, an error message will be displayed.

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: For responsive and modern styling, used via CDN.
*   **Marked.js**: A JavaScript library for parsing Markdown into HTML, used via CDN.
*   **JavaScript (ES6+)**: For fetching and rendering Markdown content.
