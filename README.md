# Melania Cano - Arquitecta Técnica

Professional website for Melania Cano, Technical Architect (Arquitecta Técnica) seeking employment opportunities in Spain.

## Website Features

- 📱 Fully responsive design
- 🏗️ Professional portfolio showcase
- 📄 CV and Portfolio download sections
- 🎨 Modern, clean design optimized for technical professionals
- 🇪🇸 Spanish language content

## Live Website

This site is hosted on GitHub Pages and available at: [https://your-username.github.io/melania-cano.com](https://your-username.github.io/melania-cano.com)

## Setup Instructions

### 1. Repository Setup
1. Create a new repository named `melania-cano.com`
2. Upload all files to the repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Save settings

### 2. Custom Domain (Optional)
To use the custom domain `melania-cano.com`:
1. Add a `CNAME` file to the root with content: `melania-cano.com`
2. Configure DNS settings with your domain provider:
   - Add CNAME record: `www` → `your-username.github.io`
   - Add A records for `@` pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

### 3. PDF Documents
Place the following PDF files in the `assets/documents/` folder:
- `CV_Melania_Cano_Arquitecta_Tecnica.pdf`
- `Portfolio_Melania_Cano_Arquitecta_Tecnica.pdf`

## File Structure

```
melania-cano.com/
├── index.html          # Main landing page
├── cv.html             # CV download page
├── portfolio.html      # Portfolio download page
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # Interactive functionality
├── assets/
│   ├── images/         # Images and photos
│   └── documents/      # PDF documents
└── README.md           # This file
```

## Content Customization

### Personal Information
Update the following in the HTML files:
- Contact email in `index.html` (line ~169)
- Phone number in `index.html` (line ~176)
- LinkedIn profile URL in `index.html` (line ~190)
- Professional photo in hero section

### Projects
The main page features 4 sample projects. Update these in `index.html` starting around line 165 with real project information.

### Professional Summary
Customize the "About Me" section in `index.html` (around line 80) with specific experience and background.

## Technical Details

- **Framework**: Pure HTML/CSS/JavaScript (no dependencies)
- **Icons**: Font Awesome 6.0.0
- **Fonts**: Inter from Google Fonts
- **Responsive**: Mobile-first design with breakpoints at 768px and 480px
- **SEO**: Meta descriptions and keywords included
- **Performance**: Optimized for fast loading on GitHub Pages

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2024 Melania Cano - All rights reserved.

This is a personal professional website. Content and design are proprietary.