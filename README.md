# Academic Portfolio Website

A modern, responsive academic portfolio website designed for researchers, professors, and academic professionals. This static website showcases your research, publications, projects, and professional information in a clean, academic style.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern Academic Styling**: Clean typography and professional layout
- **Section-based Layout**: 
  - Hero/Introduction
  - About Me
  - Research Areas
  - Publications (with filtering)
  - Projects
  - Recent News/Updates
  - CV/Resume
  - Contact Information
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Publication filtering system
  - Contact form
  - Mobile-friendly menu
- **GitHub Pages Ready**: Optimized for deployment on GitHub Pages
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Accessible**: WCAG compliant with keyboard navigation support
- **Print-Friendly**: Optimized styles for CV printing

## Quick Start

### 1. Use This Repository

1. Click "Use this template" or fork this repository
2. Clone to your local machine:
   ```bash
   git clone https://github.com/yourusername/academic-portfolio.git
   cd academic-portfolio
   ```

### 2. Customize Your Content

1. **Personal Information**: Edit `index.html` and replace all placeholder content marked with `[Your Name]`, `[Your Field]`, etc.

2. **Profile Image**: Add your profile picture as `assets/images/profile.jpg`

3. **CV File**: Add your CV as `assets/files/cv.pdf`

4. **Project Images**: Add project images to `assets/images/` (project1.jpg, project2.jpg, etc.)

5. **Update Sections**: Customize each section with your actual information:
   - Research areas and interests
   - Publications list
   - Project descriptions
   - News and updates
   - Contact information

### 3. Deploy to GitHub Pages

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

2. **Custom Domain** (optional):
   - Add a `CNAME` file with your domain name
   - Configure DNS settings with your domain provider

3. **Access Your Site**:
   - Your site will be available at `https://yourusername.github.io/repository-name`
   - Or at your custom domain if configured

## File Structure

```
academic-portfolio/
├── index.html              # Main HTML file
├── css/
│   └── style.css          # All styles and responsive design
├── js/
│   └── script.js          # Interactive functionality
├── assets/
│   ├── images/            # Profile and project images
│   │   ├── profile.jpg    # Your profile picture
│   │   ├── project1.jpg   # Project images
│   │   └── ...
│   └── files/
│       └── cv.pdf         # Your CV/Resume
├── README.md              # This file
└── CNAME                  # Custom domain (optional)
```

## Customization Guide

### Colors and Fonts

Edit `css/style.css` to customize:
- **Primary Color**: Change `#3498db` throughout the CSS
- **Fonts**: Currently uses 'Crimson Text' for headings and 'Source Sans Pro' for body text
- **Layout**: Modify grid layouts and spacing as needed

### Adding Sections

To add new sections:
1. Add HTML structure in `index.html`
2. Add navigation link in the navbar
3. Style in `css/style.css`
4. Add JavaScript functionality if needed in `js/script.js`

### Publications

The publication section supports filtering by type:
- Journal articles
- Conference papers  
- Book chapters

Add your publications in the HTML following the existing format.

### Contact Form

The contact form currently shows success/error messages but doesn't actually send emails. To make it functional:

1. **Use Formspree**: Add `action="https://formspree.io/f/your-form-id"` to the form
2. **Use Netlify Forms**: Add `netlify` attribute to the form
3. **Use EmailJS**: Implement EmailJS in the JavaScript
4. **Custom Backend**: Connect to your own server endpoint

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance

The website is optimized for performance:
- Minified CSS and JavaScript
- Optimized images
- Lazy loading support
- Efficient animations

## SEO Features

- Semantic HTML structure
- Meta tags for social media sharing
- Structured data markup ready
- Clean URLs
- Fast loading times

## Accessibility

- WCAG 2.1 AA compliant
- Keyboard navigation support
- Screen reader friendly
- Proper color contrast
- Alt text for images

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Credits

- Fonts: Google Fonts (Crimson Text, Source Sans Pro)
- Icons: Font Awesome
- Design inspiration: Modern academic websites and portfolios

## Support

If you find this template useful, please ⭐ star this repository!

For questions or support, please open an issue on GitHub.

---

**Note**: Remember to replace all placeholder content with your actual information before deploying!