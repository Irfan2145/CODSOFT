# Irfan Ansari - Student Developer Portfolio

A clean, professional portfolio website built with **HTML and CSS** to showcase my learning journey in web development and Flutter.

## 🎯 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Clean & Professional** - Simple design that reflects genuine student work
- **No JavaScript** - Pure HTML and CSS implementation
- **Easy to Customize** - Clear code structure with helpful comments
- **Semantic HTML** - Proper use of HTML5 semantic tags
- **Flexbox & Grid** - Modern CSS layout techniques

## 📂 File Structure

```
Project 1/
├── index.html          # Main HTML file
├── style.css           # All styling and responsive design
├── resume.pdf          # Your resume (add your own)
└── README.md           # This file
```

## 🚀 Getting Started

### View the Portfolio

1. Open `index.html` in your web browser
2. Navigate through the sections using the top menu
3. All links are functional and ready to customize

### Deploy Online

1. **GitHub Pages** (Free)
   - Push your files to a GitHub repository
   - Enable GitHub Pages in repository settings
   - Your portfolio will be live at `username.github.io/repository-name`

2. **Netlify** (Free)
   - Drag and drop your folder at netlify.com
   - Get a live link instantly

3. **Vercel** (Free)
   - Import your GitHub repo
   - Deploy with one click

## ✏️ Customization Guide

### 1. Update Your Photo
Replace the placeholder image in the Hero section:
```html
<img src="https://via.placeholder.com/300?text=Your+Photo" alt="Irfan Ansari">
```
Change to your image:
```html
<img src="path/to/your-photo.jpg" alt="Your Name">
```

### 2. Update Contact Information
Find the Contact section and update:
- Email address
- GitHub username/URL
- LinkedIn profile URL

### 3. Add Your Resume
- Replace `resume.pdf` with your actual resume file
- Ensure it's in the same folder as `index.html`

### 4. Add More Projects
Copy the project card structure and add new projects:
```html
<div class="project-card">
    <div class="project-image">
        <img src="project-image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Title</h3>
        <p>Project description goes here.</p>
        <div class="project-links">
            <a href="github-link" class="btn btn-secondary">GitHub</a>
            <a href="live-demo" class="btn btn-secondary">Live Demo</a>
        </div>
    </div>
</div>
```

### 5. Change Color Scheme
Edit the primary color in `style.css`:
```css
:root {
    --primary-color: #0066cc;  /* Change this to your color */
}
```

Popular alternatives:
- `#10b981` (Green)
- `#f59e0b` (Amber)
- `#ef4444` (Red)
- `#8b5cf6` (Purple)

## 📱 Responsive Breakpoints

The portfolio is optimized for:
- **Desktop** (1200px+) - Full layout with all features
- **Tablet** (768px - 1199px) - Adjusted spacing and multi-column grids
- **Mobile** (480px - 767px) - Single column, touch-friendly
- **Small Mobile** (Below 480px) - Optimized for small screens

## 🎨 Design Elements

- **Colors**
  - Primary: Blue (#0066cc)
  - Text: Dark Gray (#333333)
  - Light Text: Medium Gray (#666666)
  - Background: Off-white (#f9f9f9)

- **Typography**
  - Font: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
  - H2: 2.5rem
  - H3: 1.3rem
  - Body: 1rem

- **Spacing**
  - Uses CSS variables for consistent spacing
  - Scales responsively on smaller screens

## 📝 Sections Breakdown

1. **Navigation Bar** - Fixed top navigation with smooth scrolling
2. **Hero Section** - Eye-catching introduction with your photo
3. **About Section** - Your story and learning journey
4. **Skills Section** - Technical skills in a grid layout
5. **Projects Section** - Showcase of your projects
6. **Resume Section** - Download your resume
7. **Contact Section** - Ways to reach you
8. **Footer** - Copyright information

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern layouts with Flexbox and CSS Grid
- **Responsive Design** - Mobile-first approach
- **CSS Variables** - Easy customization and theming

## 💡 Learning Resources

This portfolio demonstrates:
- Semantic HTML structure
- CSS Flexbox for linear layouts
- CSS Grid for 2D layouts
- CSS media queries for responsiveness
- CSS variables for theming
- Professional design patterns
- Accessibility best practices

## 🚀 Future Enhancements

As you learn more, consider adding:
- [ ] JavaScript for interactive features
- [ ] Dark mode toggle
- [ ] Smooth scroll animations
- [ ] Contact form with email integration
- [ ] Blog section
- [ ] Project filtering by category
- [ ] Skills proficiency indicators
- [ ] SEO optimization
- [ ] Google Analytics
- [ ] Social media icons in footer

## 📖 How to Edit

1. Open `index.html` in any text editor (VS Code, Sublime, etc.)
2. Make changes and save
3. Refresh your browser to see updates
4. Open `style.css` to modify colors, fonts, and spacing

## ⚠️ Important Notes

- Keep `index.html` and `style.css` in the same folder
- Image paths should be relative to the HTML file location
- Test on mobile devices before deploying
- Update content as you learn new skills and complete projects

## 📧 Questions or Help?

- Check HTML/CSS syntax in your editor
- Test responsive design using browser DevTools
- Validate HTML at [validator.w3.org](https://validator.w3.org/)
- Reference CSS at [MDN Web Docs](https://developer.mozilla.org/)

---

**Built by:** Irfan Ansari  
**Date:** 2026  
**Status:** Active and regularly updated  
**License:** Free to use and modify for personal use
