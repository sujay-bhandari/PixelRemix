# Advanced Web-Based Photo Editor

A professional-grade web-based image editing application built with AngularJS and Fabric.js, offering comprehensive photo manipulation capabilities through an intuitive user interface.

## Description

PixelRemix is a powerful, feature-rich photo editing web application designed for both casual users and professionals. Built with modern web technologies, it provides a seamless editing experience directly in your browser, eliminating the need for desktop software installation.

### Why PixelRemix?

- **Professional-Grade Tools**: Access advanced editing features typically found in desktop applications
- **No Installation Required**: Edit photos directly in your web browser
- **Cross-Platform Compatibility**: Works on any device with a modern web browser
- **Real-Time Preview**: See your changes instantly as you edit
- **User-Friendly Interface**: Intuitive design makes professional editing accessible to everyone
- **Extensive Asset Library**: Built-in collection of filters, stickers, and effects

## Features

- **Image Manipulation**
  - Crop, resize, and rotate images
  - Real-time drawing with customizable brushes
  - Layer management with merge capabilities
  - Non-destructive filters and effects

- **Text and Graphics**
  - Text overlay with rich typography options
  - Custom shapes and stickers
  - Polygon creation tool
  - Opacity and transform controls

- **User Interface**
  - Responsive design for cross-device compatibility
  - Intuitive sidebar tools organization
  - Real-time preview of changes
  - Modern material design aesthetics

## Tech Stack

- AngularJS for application framework
- Fabric.js for canvas manipulation
- HTML5 Canvas for rendering
- LESS for CSS preprocessing
- Gulp for build automation

## Prerequisites

- Node.js (v12 or higher)
- NPM (v6 or higher)

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd photo-editing-web-application
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
gulp serve
```

The application will be available at `http://localhost:3000`

## Build

To create a production build:
```bash
gulp build
```

The optimized files will be available in the `dist` directory.

## Project Structure

```
├── assets/
│   ├── images/
│   └── brushes/
├── src/
│   ├── controllers/
│   ├── styles/
│   └── scripts/
├── index.html
├── gulpfile.js
└── package.json
```

## Development

The project uses Gulp for various development tasks:

- `gulp serve` - Starts development server with live reload
- `gulp build` - Creates production build
- `gulp styles` - Compiles LESS files
- `gulp scripts` - Concatenates and minifies JavaScript
- `gulp watch` - Watches for file changes

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details
