# A R Anaamika - Portfolio Website

A modern, responsive portfolio website for A R Anaamika, showcasing UX/UI design work and skills.

## 🚀 About

This portfolio website is designed for a B.Tech Electronics & Communication Engineering student passionate about UX/UI design and seeking internship opportunities. The site demonstrates design sensibility through clean, modern aesthetics and intuitive user experience.

## ✨ Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Performance Optimized**: Fast loading with efficient code
- **SEO Friendly**: Proper meta tags and semantic HTML
- **Interactive Elements**: Smooth scrolling, hover effects, and animations
- **Contact Form**: Integrated contact form for easy communication

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables and Grid/Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter & Playfair Display)

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎨 Customization Guide

### 1. Update Personal Information

**In `index.html`:**
- Replace "your.email@example.com" with your actual email
- Update social media links (LinkedIn, Behance, Dribbble, GitHub)
- Update the meta description in the `<head>` section

### 2. Add Your Photo

Replace the profile placeholder in the About section:
```html
<div class="profile-placeholder">
    <p>Your Photo Here</p>
</div>
```

With an actual image:
```html
<img src="path/to/your/photo.jpg" alt="A R Anaamika" style="width: 100%; border-radius: 20px;">
```

### 3. Add Your Projects

For each project card, update:
- Project image (replace the placeholder div)
- Tags (UX Design, UI Design, etc.)
- Title and description
- Link to case study

Example:
```html
<div class="project-image">
    <img src="path/to/project-image.jpg" alt="Project Name">
</div>
```

### 4. Customize Colors

Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;    /* Main brand color */
    --secondary-color: #ec4899;  /* Accent color */
    /* ... other colors */
}
```

### 5. Update Skills

Modify the skills lists in the Skills section to match your actual skills and tools.

### 6. Setup Contact Form

The form uses Formspree. To activate:
1. Sign up at [formspree.io](https://formspree.io)
2. Get your form endpoint
3. Replace `your-form-id` in the form action:
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

## 🌐 Deployment to GitHub Pages

### Option 1: Via GitHub Website
1. Create a repository named `aranaamika.github.io`
2. Upload all files (index.html, styles.css, script.js)
3. Go to Settings > Pages
4. Select "main" branch as source
5. Your site will be live at `https://aranaamika.github.io`

### Option 2: Via Git Commands
```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Portfolio website"

# Add remote repository
git remote add origin https://github.com/aranaamika/aranaamika.github.io.git

# Push to GitHub
git push -u origin main
```

## 📝 Content Guidelines for UX/UI Portfolio

### Projects Section
For each project, include:
- **High-quality images**: Screenshots, mockups, or prototypes
- **Clear descriptions**: Problem, solution, and impact
- **Process highlights**: Research, wireframes, testing
- **Tags**: Categorize by type (UX, UI, Mobile, Web, etc.)
- **Case studies**: Link to detailed case studies (can be Behance or Medium posts)

### About Section
Highlight:
- Your passion for design
- Technical + design background (unique selling point)
- Design philosophy
- What you're looking for (internship opportunities)

### Skills Section
Organize into:
- **Design Skills**: Research, wireframing, prototyping, etc.
- **Tools**: Figma, Adobe XD, Sketch, etc.
- **Technical Skills**: HTML/CSS, JavaScript, etc.

## 💡 Tips for Showcasing UX/UI Work

1. **Quality over quantity**: Show 3-4 strong projects rather than many weak ones
2. **Tell the story**: Explain your design process and decisions
3. **Show impact**: Include metrics or user feedback if available
4. **Keep it updated**: Regularly add new projects and skills
5. **Proofread**: Ensure all content is error-free and professional

## 🎯 Next Steps

1. [ ] Add your personal information and photo
2. [ ] Upload project images and descriptions
3. [ ] Customize colors to match your brand
4. [ ] Update skills and tools
5. [ ] Setup contact form with Formspree
6. [ ] Add resume/CV download link (optional)
7. [ ] Create detailed case studies for projects
8. [ ] Test on multiple devices and browsers
9. [ ] Deploy to GitHub Pages
10. [ ] Share your portfolio link on LinkedIn and resume

## 📧 Support

For questions or issues, feel free to reach out or create an issue in the repository.

## 📄 License

This project is open source and available for personal use.

---

**Good luck with your UX/UI design internship search! 🎨✨**
