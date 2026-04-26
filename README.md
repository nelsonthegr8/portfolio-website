# Nelson Brumaire - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a software developer.

## 🌟 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Fast Performance**: Optimized HTML, CSS, and JavaScript
- **Accessibility**: Semantic HTML and ARIA labels
- **SEO Friendly**: Proper meta tags and structure

## 📁 Project Structure

```
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # Interactive functionality
└── README.md       # Documentation
```

## 🚀 Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your browser
3. Or serve it locally:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## ✏️ Customization

### Add Your Photo
Replace the placeholder in the hero section:
```html
<!-- In index.html, find the .placeholder-image div and replace with -->
<img src="your-photo.jpg" alt="Nelson Brumaire" style="width: 400px; height: 400px; border-radius: 50%; object-fit: cover; border: 8px solid white; box-shadow: var(--shadow-lg);">
```

### Update Skills
Edit the skill tags in the Skills section:
```html
<span class="skill-tag">Your Skill</span>
```

### Add Projects
Duplicate a `.project-card` div and customize:
```html
<div class="project-card">
    <div class="project-image">
        <img src="project-screenshot.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Description...</p>
        <!-- Add tags and links -->
    </div>
</div>
```

### Change Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;  /* Change to your preferred color */
    --secondary-color: #1e40af;
    /* ... */
}
```

## 🎨 Color Scheme

- **Primary**: Blue (#2563eb)
- **Secondary**: Dark Blue (#1e40af)
- **Accent**: Light Blue (#3b82f6)
- **Text**: Dark Gray (#1f2937)
- **Background**: White/Off-white

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🛠️ Built With

- HTML5
- CSS3 (CSS Grid, Flexbox, Custom Properties)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)

## 📄 License

This project is open source and available under the MIT License.

## 📞 Contact

- **GitHub**: [nelsonthegr8](https://github.com/nelsonthegr8)
- **Website**: [nelsonbrumaire.com](https://nelsonbrumaire.com)
- **Location**: Georgia, USA

---

Built with ❤️ by Nelson Brumaire
