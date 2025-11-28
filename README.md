# Albert Saà Garriga - Personal GitHub Portfolio

This repository contains the personal portfolio website of Albert Saà Garriga, Head of Multimedia AI & Staff Researcher at Samsung Electronics.

**Live Website**: [sdruix.github.io](https://sdruix.github.io)

## Website Overview

The portfolio showcases Albert's extensive experience in Artificial Intelligence and High-Performance Computing, with a focus on:

- **Technical Leadership**: Over 15 years of experience leading world-class AI research teams
- **Innovative Research**: Contributions to computational photography, 3D vision, video understanding, and systems engineering
- **Intellectual Property**: 20+ patents and 10+ publications in top-tier conferences
- **Commercial Impact**: Successfully delivered features in flagship mobile devices

## Key Sections

1. **Executive Summary**: Introduction to Albert's unique "Research Engineer" persona
2. **Career Timeline**: Visual representation of technical evolution from PhD to leadership
3. **Research Pillars**: Deep dive into four core technical domains:
   - Computational Photography & Image Restoration
   - 3D Vision, AR & Generative AI
   - Video Understanding & Temporal Consistency
   - Systems Engineering, Privacy & MLOps
4. **Leadership Philosophy**: Approach to building and managing distributed research teams
5. **Publications & Patents**: Gallery of research output with placeholders for paper screenshots
6. **Technical Stack**: Comprehensive overview of tools and technologies

## Deployment to GitHub Pages

To deploy this website to GitHub Pages:

1. Push the code to your GitHub repository
2. Go to the repository settings
3. Scroll down to the "Pages" section
4. Under "Source", select the branch you want to deploy from (usually `main` or `master`)
5. Click "Save"
6. Your website will be available at `https://[username].github.io/[repository-name]/`

## Troubleshooting Common Issues

### Website Not Displaying Correctly

If your website appears unstyled when deployed to GitHub Pages but works correctly when running locally:

1. **Check file paths**: Ensure all file paths in `index.html` are relative and correct:
   ```html
   <link rel="stylesheet" href="styles.css">
   <script src="script.js"></script>
   ```

2. **Verify file names**: Ensure file names match exactly (case-sensitive):
   - `index.html` (not `Index.html`)
   - `styles.css` (not `Styles.css`)
   - `script.js` (not `Script.js`)

3. **Check browser console**: Open browser developer tools (F12) and check the Console tab for any error messages about failed resource loading.

4. **Hard refresh**: Try a hard refresh (Ctrl+F5 or Cmd+Shift+R) to clear browser cache.

### GitHub Pages Custom Domain

If you want to use a custom domain:

1. Create a `CNAME` file in your repository with your custom domain (e.g., `albertsaa.com`)
2. Configure your domain registrar to point to GitHub Pages

## Technical Implementation

- **Responsive Design**: Mobile-first approach with flexible grid layouts
- **Modern CSS**: Custom properties, flexbox, and grid for layout
- **Interactive Elements**: Smooth scrolling, hover effects, and mobile navigation
- **Performance Optimized**: Lightweight implementation with no external dependencies (except Font Awesome CDN)

## Browser Support

The website is compatible with all modern browsers including:
- Chrome (latest versions)
- Firefox (latest versions)
- Safari (latest versions)
- Edge (latest versions)

## Customization

To customize the content:

1. Edit `index.html` to update personal information, research details, and publications
2. Modify `styles.css` to change colors, fonts, or layout
3. Update `script.js` for additional interactivity

## Contact

For inquiries, please contact Albert Saà Garriga at albertsaagarriga@gmail.com
