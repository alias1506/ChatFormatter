# ChatFormatter

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A clean, minimal web-based text formatter designed to transform AI-generated or unformatted text into professionally formatted documents. Perfect for converting ChatGPT responses, code snippets, and markdown content into print-ready PDFs and Word documents.

## 🌐 Live Demo

**[Try ChatFormatter Now →](https://resilient-paletas-ad05c6.netlify.app/)**

## ✨ Features

- **Smart Text Processing** - Automatically removes AI watermarks, cleanup artifacts, emojis, and formats text intelligently
- **Markdown Support** - Full support for headings, bold, italic, code blocks, and bullet points
- **Code Highlighting** - Syntax-aware formatting for inline code and code blocks
- **Multi-Format Export** - Export to PDF, Word (.doc), or copy formatted text to clipboard
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Print Optimization** - PDF exports are optimized with minimal margins and 12pt font size
- **Real-time Preview** - See formatted output instantly as you process text
- **Success Notifications** - Beautiful SweetAlert2 notifications for download status
- **Mobile Optimized** - Export dropdown menu and centered layout for mobile devices

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/alias1506/ChatFormatter.git
cd ChatFormatter
```

2. Open `index.html` in your browser - that's it! No build process or dependencies required.

### Usage

1. **Paste** your unformatted text in the left panel
2. **Click** the lightning bolt button to format
3. **Export** as PDF, Word, or copy to clipboard

## 📋 Formatting Rules

ChatFormatter intelligently processes your text with these rules:

- **Headings** - Lines starting with `#` become formatted headings (same size as body text, bold)
- **Bullet Points** - Lines starting with `-`, `*`, `+`, or `•` become bulleted lists with proper indentation
- **Code Blocks** - Text between ``` markers is formatted as code blocks
- **Inline Code** - Text between backticks `` ` `` is formatted as inline code
- **Bold Text** - Text between `**` or `__` becomes bold
- **Italic Text** - Text between single `*` becomes italic
- **Indentation** - Preserves and visualizes indentation levels
- **Smart Cleanup** - Removes AI phrases like "Sure, here is...", emojis, and cleans up artifacts

## 🎨 PDF & Word Export Features

### PDF Export (via pdfMake)
- **Compact Layout**: Reduced line height (1.15) and tight margins for maximum content efficiency
- **Font Size**: 12pt uniform size for both body text and headings (headings are bold)
- **Margins**: Minimal vertical spacing optimized for dense technical content
- **Page Numbers**: Automatic "X of Y" page numbering centered at bottom
- **Code Blocks**: Gray background with preserved formatting
- **Bullet Points**: Proper bullet symbols (● for main, ◦ for sub-points)
- **Text-based**: High-quality text rendering (not image-based)
- **Line Preservation**: Text stays on single lines without breaking incorrectly

### Word Export
- **Format**: Microsoft Word (.doc) compatible
- **Inline Styles**: All formatting preserved in Word
- **Clean Output**: Only formatted content - no UI elements or toolbars

### Notifications
- **Success Alerts**: Minimal 2-second auto-dismiss notifications on successful download
- **Error Handling**: User-friendly error messages with retry suggestions
- **Design**: Matches application's minimal flat design aesthetic

## 💻 Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Tailwind CSS via CDN
- **Vanilla JavaScript** - No frameworks, pure ES6+
- **pdfMake** - Professional PDF generation library
- **SweetAlert2** - Beautiful, responsive alert notifications
- **Google Fonts** - Inter font family for clean typography

## 📁 Project Structure

```
ChatFormatter/
├── index.html      # Main HTML structure
├── script.js       # Core formatting logic
├── style.css       # Custom styles and print CSS
└── README.md       # Documentation
```

## 🌐 Browser Support

- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## 📝 Use Cases

- Format ChatGPT responses for documentation
- Clean up AI-generated content
- Convert markdown to formatted documents
- Create print-ready code documentation
- Format interview questions and answers
- Export formatted notes and tutorials

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ for better formatting</p>
