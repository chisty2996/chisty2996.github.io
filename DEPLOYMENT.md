# Deployment Instructions for GitHub Pages

## Quick Setup Guide

### 1. Repository Setup
1. Fork or download this repository
2. Create a new GitHub repository named `your-username.github.io` or any other name
3. Upload all files to your repository

### 2. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section in the sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### 3. Access Your Website
- Your website will be available at: `https://your-username.github.io/repository-name`
- If your repository is named `your-username.github.io`, it will be available at: `https://your-username.github.io`

### 4. Custom Domain (Optional)
1. Purchase a domain name from any registrar
2. Update the `CNAME` file with your domain (e.g., `www.yourdomain.com`)
3. Configure DNS settings with your domain registrar:
   - Add CNAME record: `www` → `your-username.github.io`
   - Add A records for apex domain pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153  
     - 185.199.110.153
     - 185.199.111.153
4. In repository Settings > Pages, add your custom domain

### 5. SSL Certificate
GitHub Pages automatically provides SSL certificates for both `github.io` domains and custom domains.

## Customization Checklist

Before going live, make sure to:

- [ ] Replace all `[Your Name]` placeholders with your actual name
- [ ] Update `[Your Field]` with your research area
- [ ] Replace `[Your University/Institution]` with your affiliation
- [ ] Add your actual profile photo as `assets/images/profile.jpg`
- [ ] Upload your CV as `assets/files/cv.pdf`
- [ ] Update all sections with your real information:
  - [ ] About section with your biography
  - [ ] Research areas and interests
  - [ ] Publications list
  - [ ] Projects with descriptions
  - [ ] Recent news and updates
  - [ ] Contact information
- [ ] Update social media links in the hero section
- [ ] Add project images to `assets/images/`
- [ ] Test all links and functionality
- [ ] Optimize images for web (compress if needed)

## Alternative Deployment Options

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on every commit
3. Get free SSL and custom domain support

### Vercel
1. Import your GitHub repository to Vercel
2. Automatic deployments and performance optimization
3. Free tier includes custom domains

### Traditional Web Hosting
1. Download all files from your repository
2. Upload to any web hosting service via FTP
3. Works with shared hosting, VPS, or dedicated servers

## Performance Optimization

For better performance:
1. Compress images using tools like TinyPNG
2. Enable Gzip compression (automatic on GitHub Pages)
3. Minimize CSS/JS if needed (current files are already optimized)
4. Consider using WebP format for images

## SEO Optimization

1. Update meta tags in `index.html`:
   - Title tag with your name and field
   - Description meta tag
   - Keywords meta tag
2. Add Google Analytics (optional)
3. Submit to Google Search Console
4. Create a sitemap.xml (optional for better indexing)

## Maintenance

- Regularly update your publications and news
- Keep your CV current
- Update project information
- Monitor site performance and fix any issues
- Backup your content regularly

## Troubleshooting

### Site Not Loading
- Check if GitHub Pages is enabled in repository settings
- Ensure all files are in the root directory or properly structured
- Wait 5-10 minutes after enabling Pages for propagation

### Images Not Displaying
- Check file paths and names (case-sensitive)
- Ensure images are in the correct directory
- Verify image file formats (JPG, PNG, WebP)

### Custom Domain Issues
- Verify DNS settings with your domain registrar
- Check CNAME file content
- Allow 24-48 hours for DNS propagation

For additional help, consult the [GitHub Pages documentation](https://docs.github.com/en/pages) or open an issue in this repository.