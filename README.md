# Min Ko Naing - Portfolio Website

A modern, responsive portfolio website showcasing my work as a Full Stack Developer. Built with vanilla HTML, CSS, and JavaScript, featuring smooth animations, PWA capabilities, and SEO optimization.

## 🌟 Features

### ✨ Design & User Experience

- **Modern Glassmorphism Design** - Beautiful glass-like effects with backdrop blur
- **Smooth Animations** - CSS transitions and keyframe animations for enhanced UX
- **Responsive Design** - Fully responsive across all devices (mobile, tablet, desktop)
- **Dark Theme** - Elegant dark color scheme with accent colors
- **Interactive Elements** - Hover effects, smooth scrolling, and dynamic content

### 🚀 Performance & SEO

- **PWA Ready** - Progressive Web App with manifest.json and service worker support
- **SEO Optimized** - Meta tags, structured data, sitemap.xml, and robots.txt
- **Fast Loading** - Optimized CSS, minified files, and efficient asset loading
- **Accessibility** - ARIA labels, semantic HTML, and keyboard navigation

### 📱 Technical Features

- **Dynamic Content Loading** - Projects and experience data loaded from JSON files
- **Image Optimization** - Responsive images with lazy loading
- **Contact Form** - Functional contact form with validation
- **Social Media Integration** - Direct links to LinkedIn, GitHub, Telegram, and Line
- **Project Showcase** - Detailed project galleries with technology tags

## 🛠️ Technologies Used

### Frontend

- **HTML5** - Semantic markup and modern HTML features
- **CSS3** - Advanced styling with Flexbox, Grid, and custom properties
- **JavaScript (ES6+)** - Vanilla JS for interactivity and dynamic content
- **Font Awesome** - Icon library for UI elements

### Development Tools

- **JSON** - Data storage for projects and experience
- **PWA Manifest** - Progressive Web App configuration
- **SEO Tools** - Meta tags, structured data, and optimization

### Deployment

- **XAMPP** - Local development environment
- **Static Hosting Ready** - Can be deployed to any static hosting service

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── css/
│   ├── style.css           # Main stylesheet
│   ├── style.min.css       # Minified CSS for production
│   └── style_backup.css    # Backup stylesheet
├── js/
│   └── script.js           # Main JavaScript file
├── data/
│   ├── projects.json       # Project data
│   ├── experience.json     # Work experience data
│   └── certificates.json   # Certifications data
├── assets/
│   ├── logo.png            # Site logo
│   ├── profile.png         # Profile image
│   ├── main-bento.jpg      # Hero background
│   └── svg/                # SVG icons for technologies
├── project_images/         # Project screenshots and images
├── manifest.json           # PWA manifest
├── sitemap.xml            # SEO sitemap
├── robots.txt             # Search engine directives
├── .htaccess              # Apache configuration
├── favicon.ico            # Site favicon
└── SEO_CHECKLIST.md       # SEO optimization checklist
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- XAMPP (for local development) or any web server
- Text editor (VS Code, Sublime Text, etc.)

### Installation

1. **Clone or Download**

   ```bash
   # If using git
   git clone [repository-url]
   cd portfolio

   # Or download and extract the ZIP file
   ```

2. **Local Development Setup**

   ```bash
   # Using XAMPP
   # Copy the portfolio folder to htdocs/
   # Access via: http://localhost/portfolio/

   # Using Python (alternative)
   python -m http.server 8000
   # Access via: http://localhost:8000/

   # Using Node.js (alternative)
   npx serve .
   # Access via: http://localhost:3000/
   ```

3. **Production Deployment**
   - Upload all files to your web hosting service
   - Ensure the web server supports static file serving
   - Update any absolute URLs in the code if needed

## 📋 Configuration

### Customizing Content

1. **Update Personal Information**

   - Edit `index.html` to change name, title, and meta information
   - Update social media links in the navigation and footer

2. **Modify Projects**

   - Edit `data/projects.json` to add/remove projects
   - Add project images to `project_images/` directory
   - Update technology tags and descriptions

3. **Update Experience**

   - Edit `data/experience.json` to modify work experience
   - Add new positions, companies, and responsibilities

4. **Customize Styling**
   - Modify `css/style.css` for design changes
   - Update color variables in the `:root` selector
   - Adjust animations and transitions

### SEO Configuration

1. **Meta Tags** - Update in `index.html` head section
2. **Structured Data** - Modify JSON-LD schema in `index.html`
3. **Sitemap** - Update `sitemap.xml` with your domain
4. **Robots.txt** - Configure search engine directives

## 🎨 Customization Guide

### Colors and Theme

The color scheme is defined using CSS custom properties in `css/style.css`:

```css
:root {
  --primary-color: #212121;
  --secondary-color: #007bff;
  --accent-color: #00d4ff;
  --text-color: #ffffff;
  --background-color: #0f1419;
}
```

### Adding New Sections

1. Add HTML structure to `index.html`
2. Create corresponding CSS styles in `css/style.css`
3. Add JavaScript functionality in `js/script.js` if needed

### Responsive Design

The site uses mobile-first responsive design with breakpoints:

- Mobile: `< 768px`
- Tablet: `768px - 1024px`
- Desktop: `> 1024px`

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 PWA Features

The portfolio is configured as a Progressive Web App with:

- **Installable** - Can be added to home screen
- **Offline Capable** - Basic offline functionality
- **App-like Experience** - Full-screen mode and native feel
- **Fast Loading** - Optimized for performance

## 🚀 Performance Optimizations

- **Minified CSS** - Production-ready minified stylesheet
- **Optimized Images** - Compressed and properly sized images
- **Lazy Loading** - Images load as needed
- **Efficient Animations** - Hardware-accelerated CSS transforms
- **Preconnect Links** - Faster external resource loading

## 📞 Contact & Support

- **Portfolio**: [https://merxy.club](https://merxy.club)
- **LinkedIn**: [Min Ko Naing](https://www.linkedin.com/in/min-ko-naing/)
- **GitHub**: [minkonaing99](https://github.com/minkonaing99)
- **Telegram**: [@mk_naing](https://t.me/mk_naing)
- **Line**: [mk_naing](https://line.me/ti/p/~mk_naing)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Font Awesome** - For the beautiful icons
- **Google Fonts** - For typography
- **CSS Grid & Flexbox** - For modern layout techniques
- **PWA Standards** - For progressive web app features

---

**Built with ❤️ by Min Ko Naing**

_Full Stack Developer | Bangkok, Thailand_
