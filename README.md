# Personal Portfolio Website

A modern, responsive portfolio website showcasing skills in IT, Graphic Design, and Web Development.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Portfolio**: Filter projects by category (Web Development, Graphic Design, Applications)
- **Skills Showcase**: Visual skill bars with progress indicators
- **Resume/CV Section**: Professional timeline layout for education and experience
- **Contact Form**: Functional contact form with validation
- **Smooth Animations**: CSS animations and JavaScript interactions
- **SEO Optimized**: Proper meta tags and semantic HTML

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal information and statistics
3. **Skills**: Technical skills organized by category with progress bars
4. **Portfolio**: Project showcase with filtering capabilities
5. **Resume/CV**: Professional timeline of education and experience
6. **Contact**: Contact information and functional contact form

## Customization Guide

### Personal Information

1. **Update Name**: Replace "Your Name" throughout the HTML file
2. **Contact Information**: Update email, phone, and location in the contact section
3. **Social Media**: Add your social media links in the contact section
4. **Profile Image**: Replace the placeholder icon with your actual profile image

### Skills Section

Update the skills in `index.html`:

```html
<div class="skill-item">
    <span>Your Skill</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### Portfolio Projects

Add your projects in the portfolio section:

```html
<div class="portfolio-item" data-category="web">
    <div class="portfolio-image">
        <!-- Add your project image here -->
    </div>
    <div class="portfolio-content">
        <h3>Project Title</h3>
        <p>Project description</p>
        <div class="portfolio-tags">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
    </div>
</div>
```

### Resume/CV Content

Update the timeline items in the resume section with your actual:
- Education history
- Work experience
- Certifications

### Colors and Styling

The website uses a modern color scheme:
- Primary Blue: `#2563eb`
- Accent Yellow: `#fbbf24`
- Dark Gray: `#1f2937`
- Light Gray: `#f8fafc`

You can customize colors in the `styles.css` file.

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. **Download/Clone** the files to your local machine
2. **Customize** the content as described above
3. **Test** the website locally by opening `index.html` in a browser
4. **Deploy** to your preferred hosting service (GitHub Pages, Netlify, Vercel, etc.)

## Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop your folder to [netlify.com](https://netlify.com)
2. Your site will be live instantly

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized CSS animations
- Lazy loading for images
- Smooth scrolling
- Responsive images
- Minimal JavaScript footprint

## SEO Optimization

- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Alt text for images
- Fast loading times

## Accessibility

- Keyboard navigation support
- Screen reader friendly
- High contrast colors
- Proper ARIA labels
- Focus indicators

## Future Enhancements

- Blog section
- Dark mode toggle
- Multi-language support
- Project case studies
- Testimonials section
- Integration with CMS

## Support

If you need help customizing your portfolio:

1. Check the HTML comments for guidance
2. Review the CSS classes for styling options
3. Modify the JavaScript for additional functionality

## License

This portfolio template is free to use for personal and commercial projects.

---

**Created with ❤️ for showcasing your amazing work!** 