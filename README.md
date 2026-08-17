# Portfolio Backbone

A modern, creative developer portfolio template built with HTML5, CSS3, and Vanilla JavaScript.

## 📁 Project Structure

```
portfolio/
├── main.html          # Main HTML file with all sections
├── styles.css         # Complete styling with creative aesthetic
├── script.js          # Vanilla JS for interactivity
└── README.md          # This file
```

## 🎨 Features

- **Responsive Design** - Mobile-first approach, looks great on all devices
- **Smooth Animations** - Fade-in effects, floating animations, gradient shifts
- **Modern UI** - Clean, minimalist design with creative color scheme
- **Interactive Elements** - Form validation, smooth scrolling, scroll-to-top button
- **Performance Optimized** - Minimal dependencies, pure vanilla JavaScript
- **Accessibility** - Semantic HTML, proper contrast ratios

## 🔧 Customization Guide

### 1. Update Personal Information
Open `main.html` and replace:
- `Your Name` - Your actual name
- `Full Stack Developer | Creative Coder | Problem Solver` - Your tagline
- Project titles, descriptions, and links
- Skills and technologies
- Social media links

### 2. Change Color Scheme
Edit the CSS variables in `styles.css` (lines 7-14):
```css
:root {
    --primary: #667eea;      /* Main color */
    --secondary: #764ba2;    /* Secondary color */
    --accent: #f093fb;       /* Accent color */
    --dark: #0f0f1e;         /* Dark background */
    --light: #f5f7fa;        /* Light background */
}
```

### 3. Add Your Projects
In `main.html`, the projects section contains project cards. Each card has:
- **Background gradient** - Change the `style="background: linear-gradient(...)"` to customize colors
- **Title & Description** - Update project info
- **Tags** - Add relevant tech stack tags
- **Link** - Add link to project demo/repository

### 4. Configure Contact Form
By default, the form logs to console. To make it functional:
1. Use Formspree, EmailJS, or your own backend
2. Update the form submission handler in `script.js`

### 5. Add Social Links
In the Contact section, update:
```html
<a href="#" aria-label="GitHub">GitHub</a>
<a href="#" aria-label="LinkedIn">LinkedIn</a>
<a href="#" aria-label="Twitter">Twitter</a>
<a href="#" aria-label="Email">Email</a>
```

## 🚀 Quick Start

1. Open `main.html` in your browser
2. Replace placeholder content with your information
3. Customize colors in `styles.css`
4. Update social links and form handler
5. Deploy to Netlify, Vercel, or GitHub Pages

## 📱 Responsive Breakpoints

- **Desktop** - 1200px and above
- **Tablet** - 768px to 1199px
- **Mobile** - Below 768px (with hamburger menu)

## ✨ Included Sections

1. **Navigation Bar** - Fixed header with smooth scroll links
2. **Hero Section** - Eye-catching intro with animated element
3. **About** - Personal introduction with stats
4. **Projects** - Showcase your work with descriptions
5. **Skills** - Organized skill categories
6. **Contact** - Contact form and social links
7. **Footer** - Copyright information

## 🎯 JavaScript Features

- **Mobile Menu Toggle** - Hamburger menu for mobile devices
- **Active Navigation** - Highlights current section
- **Form Validation** - Client-side email and field validation
- **Intersection Observer** - Fade-in animations on scroll
- **Scroll to Top** - Floating button to jump to top
- **Parallax Effect** - Subtle background movement

## 💡 Tips for Enhancement

- Add project images/screenshots
- Implement dark mode toggle
- Add a blog section
- Connect to a backend for form submissions
- Add PDF resume/CV download
- Implement project filtering
- Add testimonials section
- Integrate with GitHub API for live project data

## 📝 Notes

- All animations use CSS transitions for smooth performance
- Uses modern CSS features (Grid, Flexbox, CSS Variables)
- No external libraries required - pure vanilla implementation
- SEO-friendly semantic HTML structure

## 🎓 Learning Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [Web.dev](https://web.dev/)

---

**Ready to showcase your work! 🚀**
