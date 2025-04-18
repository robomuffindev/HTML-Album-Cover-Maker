# Album Cover Generator

A client-side JavaScript application that lets users create custom album covers using their own images. The generator allows customization of text, fonts, colors and image cropping with zero server dependencies.

![AlbumCoverGenerator_Screen_v2](https://github.com/user-attachments/assets/2fc489b6-1733-4ccb-aaea-a52af9037a7b)

## Features

- **100% Client-side**: All processing happens in the browser - no server required
- **Custom Text**: Add artist name and song title with customizable font size and color
- **Font Options**: 
  - Uses Aldrich font by default (included with the application)
  - Optional Google Fonts integration with 20+ popular font choices
  - Apply different fonts to artist name and song title
- **Customization Options**:
  - Adjustable output dimensions
  - Color selection for text elements
  - Square cropping option for source images
- **Export**: Save your creations as PNG files

## Live Demo

Try the Album Cover Generator here: [Live Demo Link](#)

## Setup

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/album-cover-generator.git
   ```

2. Open `index.html` in your web browser. That's it!

No build process, package installation, or server setup required.

## Usage Instructions

1. Upload an image
2. Enter artist name and song title
3. Customize font sizes and colors
4. (Optional) Enable Google Fonts for additional typography options
5. Click "Preview" to see your changes
6. Click "Download Cover" to save your creation

## Font Options

The generator includes two font sources:

- **Default**: Uses the included Aldrich font (Aldrich-Regular.ttf)
- **Google Fonts**: When enabled, loads fonts on-demand from Google's CDN

## File Structure

```
album-cover-generator/
├── index.html         # Main application
├── Aldrich-Regular.ttf # Default font file
└── preview.png        # Screenshot for README
```

## Browser Compatibility

Tested and working in:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Aldrich font created by Mattox Shuler (from Google Fonts)
- Bootstrap for styling
