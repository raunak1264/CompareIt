# Code Comparison Tool

A modern, browser-based tool for comparing code and text side by side with syntax highlighting, making it easy to identify differences between files or code snippets.

## Features

- **Side-by-Side Comparison**: View original and modified code next to each other
- **Unified Diff View**: See all changes in a single consolidated view
- **Syntax Highlighting**: Support for multiple programming languages
- **Line Numbers**: Toggle line numbers on and off
- **File Upload**: Load files directly from your computer
- **Download**: Save your comparison results as an HTML file
- **Responsive Design**: Works on both desktop and mobile devices
- **Keyboard Shortcuts**: Enhance productivity with keyboard shortcuts

## Supported Languages

- JavaScript
- Python
- Java
- C#
- C++
- PHP
- HTML
- CSS
- JSON
- XML
- Markdown
- SQL
- Plain Text

## How to Use

1. **Access the Tool**: Go to https://raunak1264.github.io/CompareIt/
2. **Input Code**:
   - Paste or type code/text into both panels
   - Or use the "Load File" buttons to upload files from your computer
3. **Select Options**:
   - Choose the appropriate language for syntax highlighting
   - Select your preferred view mode (Side by Side or Unified Diff)
4. **Compare**: Click the "Compare Differences" button to highlight the changes
5. **Analyze**: Differences are highlighted with color coding
   - Added content appears with a green background
   - Removed content appears with a red background and strikethrough
6. **Download**: Save your comparison results for sharing or future reference

## Keyboard Shortcuts

- `Ctrl+Enter`: Compare differences
- `Ctrl+L`: Toggle line numbers
- `Ctrl+R`: Reset both editors

## Local Development

To run this tool locally:

1. Clone the repository:
   ```
   gh repo clone raunak1264/CompareIt
   ```

2. Open `index.html` in your browser.

That's it! No build process or server setup required.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to help improve this tool.

Ideas for future enhancements:
- Word-level diff highlighting
- More language support
- Custom themes
- Persistent storage of comparisons
- Integration with version control systems

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Credits

- Built with vanilla JavaScript, HTML, and CSS
- Uses [diff-match-patch](https://github.com/google/diff-match-patch) for diff calculation
- Uses [highlight.js](https://highlightjs.org/) for syntax highlighting
