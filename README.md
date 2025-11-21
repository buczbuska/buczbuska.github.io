# Personal Academic Website

A professional, responsive personal academic website built for GitHub Pages. Features sections for bio, research, curriculum vitae (CV), and contact information.

## Features

### Sections
- **Hero Section**: Eye-catching welcome banner with professional title
- **About Me**: Personal bio with education highlights and areas of expertise
- **Research**: Showcase publications, projects, and citation statistics
- **Curriculum Vitae**: Comprehensive academic CV including:
  - Education history
  - Professional experience
  - Honors & awards
  - Teaching experience
  - Service & leadership roles
  - Skills & expertise
  - PDF download option
- **Contact**: Email, professional profiles (LinkedIn, Twitter, Google Scholar, GitHub), and office location

### Design
- Clean, professional design suitable for academia
- Responsive layout that works on desktop, tablet, and mobile devices
- Smooth scrolling navigation
- Mobile-friendly hamburger menu
- Fade-in animations on scroll
- Sticky navigation bar
- Modern blue gradient color scheme

## Getting Started

### Customization

1. **Edit `index.html`**: Replace all placeholder text in square brackets with your actual information:
   - `[Your Name]` - Your full name
   - `[Your Field]` - Your area of study/research
   - `[Your University]` - Your educational institutions
   - `[Your Title/Position]` - Your current position
   - `[Your Institution]` - Your current institution
   - And other placeholders throughout the document

2. **Update Contact Information**: 
   - Email address
   - Social media links
   - Office address

3. **Add Your Content**:
   - Publications and research projects
   - CV details
   - Professional achievements

4. **Optional - Add PDF CV**: Place a `cv.pdf` file in the root directory for the download button to work

### Local Testing

To test the website locally:

```bash
# Using Python 3
python3 -m http.server 8000

# Then open http://localhost:8000 in your browser
```

### Deployment

This website is designed for GitHub Pages. Simply push to the main branch and enable GitHub Pages in your repository settings.

## File Structure

```
.
├── index.html      # Main HTML file with all content
├── styles.css      # CSS styling
├── script.js       # JavaScript for interactive features
└── README.md       # This file
```

## Customization Tips

- **Colors**: Edit the CSS variables in `styles.css` to change the color scheme
- **Fonts**: The website uses the Inter font from Google Fonts. You can change this in the HTML head section
- **Layout**: All sections use a consistent container width for easy modification
- **Content**: All sections are clearly marked in the HTML for easy editing

## Browser Support

Works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use this template for your own academic website.
