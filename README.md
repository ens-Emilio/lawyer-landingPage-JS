# Landing Page - Silva & Advogados

A professional landing page for a law firm built with Vite, Tailwind CSS, and vanilla JavaScript.

## Overview

This is a responsive landing page designed for a law firm (Silva & Advogados) specializing in multiple areas of law including Civil Law, Labor Law, Social Security Law, Family Law, Corporate Law, and Criminal Law.

## Features

- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop
- **Modern UI**: Clean and professional design with smooth animations
- **Sections**:
  - Navigation with mobile menu
  - Hero section with call-to-action buttons
  - Areas of Practice (6 practice areas)
  - About section
  - Testimonials
  - Contact form
  - Footer with social media links
- **Interactive Elements**:
  - Smooth scroll navigation
  - Mobile hamburger menu
  - Form validation
  - WhatsApp direct contact button
  - Hover effects on cards and buttons

## Technologies Used

- **Vite** - Build tool and development server
- **Tailwind CSS v4** - Utility-first CSS framework
- **Vanilla JavaScript** - Interactive functionality
- **Google Fonts** - Inter and Merriweather fonts

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Navigate to the project directory:
```bash
cd langingpage-advogado
```

3. Install dependencies:
```bash
npm install
```

### Development

Start the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:5173`

### Build

Create a production build:
```bash
npm run build
```

### Preview Production Build

Preview the built project:
```bash
npm run preview
```

## Project Structure

```
langingpage-advogado/
├── public/
│   └── vite.svg
├── src/
│   ├── main.js
│   ├── counter.js
│   ├── style.css
│   └── javascript.svg
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── README.md
```

## Customization

### Colors

The color scheme is defined in `src/style.css` using CSS variables:

- Primary colors: `#0f172a` (dark blue) to `#f8fafc` (light)
- Accent colors: `#d97706` (amber) variations

### Areas of Practice

To modify the practice areas, edit the corresponding section in `index.html`. Each area is represented by a card with:
- Icon
- Title
- Description
- "Learn more" link

### Contact Form

The form submits to `#contato` section. Currently, it shows a success message on submission. To connect with a backend service, modify the form handler in `src/main.js`.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**ens-Emilio**

## Deployment

### GitHub Pages

This project is configured for deployment on GitHub Pages.

1. Update the `homepage` field in `package.json` with your GitHub Pages URL:
   ```json
   "homepage": "https://your-username.github.io/langingpage-advogado"
   ```

2. Install the gh-pages package (optional, for automatic deployment):
   ```bash
   npm install --save-dev gh-pages
   ```

3. Deploy to GitHub Pages:
   ```bash
   npm run deploy
   ```

   Or push to main branch and use GitHub Actions.

### Manual Deployment

1. Build the project:
   ```bash
   npm run build
   ```

2. The built files will be in the `dist` folder

3. Deploy the contents of `dist` to GitHub Pages:
   - Go to your repository on GitHub
   - Navigate to Settings > Pages
   - Select the `dist` folder as the source
   - Save

## Credits

- Images: [Unsplash](https://unsplash.com/)
- Icons: Built with SVG
- Fonts: [Google Fonts](https://fonts.google.com/)
