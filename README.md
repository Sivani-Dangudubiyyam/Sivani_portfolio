# Portfolio Website - Sivani Dangudubiyyam

A modern, responsive portfolio website showcasing AI and software development skills, built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Smooth Scrolling**: Navigation with smooth scroll behavior
- **Interactive Elements**: Hover effects, animations, and transitions
- **Mobile Menu**: Hamburger menu for mobile navigation
- **Contact Form**: Functional contact form (ready for backend integration)
- **Experience Timeline**: Visual timeline showcasing internships and work experience
- **Education Section**: Display of academic achievements and certifications

## Sections

1. **Hero Section**: Introduction highlighting AI & Software Development expertise
2. **About**: Personal information, education, and key statistics
3. **Experience**: Timeline of internships at Edunet Foundation (Microsoft/SAP & IBM collaborations)
4. **Skills**: Comprehensive showcase of technical skills including:
   - Programming languages (Python, HTML, CSS, JavaScript)
   - ML/AI Frameworks (TensorFlow, Keras, Hugging Face)
   - Databases (SQLite, MySQL)
   - Developer Tools (Git, n8n, VS Code, etc.)
5. **Projects**: Featured projects including:
   - Learning Path Generator (Streamlit, MCP, Google AI Studio)
   - Automated Research Newsletter (n8n automation)
   - Wikipedia Search Application
6. **Contact**: Contact information and form

## Customization

### Personal Information
1. Update `index.html`:
   - Replace "Your Name" with your actual name
   - Update email, LinkedIn, and GitHub links
   - Modify project descriptions and links
   - Update skills and technologies

2. Update `styles.css`:
   - Change color scheme in `:root` variables
   - Adjust fonts, spacing, and sizes as needed

### Adding Projects
Add new project cards in the projects section:
```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">Project Name</div>
    </div>
    <div class="project-content">
        <h3>Project Title</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Tech1</span>
            <span>Tech2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

You can deploy this portfolio to:
- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Drag and drop deployment
- **Vercel**: Fast deployment with Git integration
- **Any static hosting service**

## License

Feel free to use this template for your own portfolio!

