# DevGenix Studio Website

A modern, responsive website for DevGenix Studio, a creative web agency. Built with HTML, Tailwind CSS, and JavaScript.

## Features

- Responsive design for all devices
- Dark mode support
- Smooth scrolling and animations
- Blog system with listing and post pages
- Contact form
- Modern and clean UI
- SEO optimized

## Tech Stack

- HTML5
- Tailwind CSS
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/devgenix-studio.git
cd devgenix-studio
```

2. Install dependencies:
```bash
npm install
```

3. Build the CSS:
```bash
npx tailwindcss -i ./css/style.css -o ./css/output.css --watch
```

4. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## Project Structure

```
devgenix-studio/
├── index.html
├── blog.html
├── blog/
│   └── post-title.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   ├── favicon.png
│   ├── portfolio-1.jpg
│   ├── portfolio-2.jpg
│   └── ...
└── README.md
```

## Customization

### Colors

The color scheme can be modified in the `tailwind.config.js` file:

```javascript
theme: {
  extend: {
    colors: {
      primary: '#2563eb',
      secondary: '#1e40af',
      dark: '#1f2937',
      light: '#f3f4f6',
    }
  }
}
```

### Fonts

The website uses Inter and Poppins fonts from Google Fonts. You can change them in the HTML files and update the font-family in the Tailwind configuration.

## Adding Blog Posts

1. Create a new HTML file in the `blog` directory
2. Copy the structure from `post-title.html`
3. Update the content, meta tags, and images
4. Add the post to the grid in `blog.html`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

DevGenix Studio - hello@devgenix.studio

Project Link: [https://github.com/yourusername/devgenix-studio](https://github.com/yourusername/devgenix-studio) 