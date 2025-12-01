# QR Menu Project - Frontend

A modern, responsive QR code-based digital menu application for restaurants. This frontend application allows customers to browse menu categories, view products, request bills, call waiters, and leave reviews directly from their mobile devices.

## Features

- 📱 *Responsive Design*: Mobile-first design optimized for QR code scanning
- 🍽 *Menu Browsing*: Browse menu categories and view detailed product information
- 💰 *Bill Request*: Request bill by selecting table number
- 🧑‍🍳 *Waiter Call*: Call waiter functionality with table selection
- ⭐ *Review System*: Rate and review the restaurant experience
- 🌐 *Multi-language Support*: Language switching capability
- 💱 *Currency Selection*: Multiple currency support
- 🎨 *Modern UI*: Clean and intuitive user interface built with Bootstrap 5

## Technologies Used

- *HTML5*: Semantic markup
- *CSS3/SCSS*: Styling with Sass preprocessor
- *JavaScript*: Interactive functionality
- *Bootstrap 5.2.3*: Responsive framework
- *Gulp*: Build automation and task runner
- *Sass*: CSS preprocessor

## Project Structure


qr-menu-project-frontend/
├── assets/
│   ├── css/              # Compiled CSS files
│   ├── img/              # Images and icons
│   │   ├── icons/        # SVG and PNG icons
│   │   └── logo.png      # Restaurant logo
│   ├── js/               # JavaScript files
│   └── sass/             # SCSS source files
│       ├── components/   # Component styles
│       ├── pages/        # Page-specific styles
│       └── src/          # Base styles (colors, fonts, reset)
├── index.html            # Main menu page
├── product-page.html     # Product listing page
├── gulpfile.js           # Gulp configuration
└── package.json          # Project dependencies


## Prerequisites

Before you begin, ensure you have the following installed:

- *Node.js* (v14 or higher)
- *npm* (Node Package Manager)

## Installation

1. Clone the repository or download the project files

2. Install dependencies:
bash
npm install


## Development

### Compile SCSS to CSS

To compile SCSS files to CSS:
bash
npx gulp sass


### Watch for Changes

To automatically compile SCSS files when changes are detected:
bash
npx gulp watch


This will watch for changes in the assets/sass/ directory and automatically compile them to assets/css/.

## Usage

1. Open index.html in a web browser to view the main menu page
2. Navigate through menu categories
3. Click on categories to view products in product-page.html
4. Use the bottom action buttons to:
   - Request bill (select table number)
   - Call waiter (select table number)
   - Leave a review (rate with stars and add comments)

## Customization

### Styling

The project uses SCSS for styling. Main style files are located in:
- assets/sass/style.scss - Main stylesheet
- assets/sass/src/ - Base styles (colors, fonts, reset)
- assets/sass/components/ - Reusable components
- assets/sass/pages/ - Page-specific styles

To customize colors, fonts, or other design elements, edit the files in assets/sass/src/.

### Content

- Update restaurant name in index.html and product-page.html
- Replace logo image at assets/img/logo.png
- Update product images and categories as needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Author

*keremgunes.com.tr*

## License

ISC

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Notes

- This is a frontend-only application
- Backend integration may be required for full functionality (bill requests, waiter calls, reviews)
- Ensure all image paths are correct before deployment
- Test on mobile devices for optimal QR code scanning experience
