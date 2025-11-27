# Cancer Awareness & Support

A modern, fully responsive website dedicated to raising awareness about cancer, providing support to patients and families, and promoting cancer research.

![Cancer Awareness Website](https://images.unsplash.com/photo-1576091160550-2173dba999ef?auto=format&fit=crop&w=1200&h=600&q=80)

## ✨ Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Modern Animations**: Smooth CSS animations and transitions throughout
- **Hero Section**: Compelling hero section with floating animations and call-to-action buttons
- **About Section**: Clear mission statement with card-based layout showcasing key initiatives
- **Resources Hub**: Comprehensive resources for cancer information and support
- **Daily Quotes**: Inspirational quotes to motivate and encourage visitors
- **Contact Form**: Easy-to-use contact form with validation for inquiries
- **Progress Bar**: Visual scroll progress indicator
- **Interactive Navigation**: Smooth scrolling with dynamic navbar styling
- **Social Integration**: Footer with social media links
- **Accessibility**: Semantic HTML and ARIA labels for better accessibility

## 📋 Sections

### 1. **Hero Section**
- Eye-catching gradient background
- Professional medical imagery
- Clear call-to-action buttons
- Floating animations for visual engagement

### 2. **About Section**
- Mission statement
- Three key pillars:
  - **Awareness**: Education and prevention
  - **Support**: Emotional and practical assistance
  - **Research**: Funding innovative treatments

### 3. **Resources Section**
- **Early Detection**: Screening and symptom information
- **Support Groups**: Community connections
- **Treatment Options**: Various therapy approaches
- **Caregiver Resources**: Support for loved ones

### 4. **Inspiration Section**
- Daily motivational quotes
- Rotating quote system
- Interactive quote refresh button

### 5. **Contact Section**
- Professional contact form
- Name, email, and message fields
- Form validation
- Success notification

### 6. **Footer**
- Copyright information
- Social media links
- Quick navigation

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with gradients and animations
- **Bootstrap 5**: Responsive grid system and components
- **JavaScript**: Interactivity and form handling
- **Font Awesome**: Professional icons
- **Animate.css**: Pre-built animation library

## 📦 Dependencies

All dependencies are loaded from CDN:

\`\`\`html
<!-- Bootstrap 5 CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Animate.css -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">

<!-- Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
\`\`\`

## 🚀 Quick Start

### Option 1: Direct File Usage
1. Download `index.html`
2. Open in your web browser
3. No installation required!

### Option 2: Local Server
\`\`\`bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using Live Server (VS Code Extension)
# Right-click on index.html → Open with Live Server
\`\`\`

Then navigate to `http://localhost:8000` in your browser.

### Option 3: Deploy to Vercel
\`\`\`bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
\`\`\`

### Option 4: GitHub Pages
1. Fork or upload this repository to GitHub
2. Go to Settings → Pages
3. Set source to main branch
4. Your site will be live at `https://yourusername.github.io/repo-name`

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization

### Colors
Edit the CSS variables in the `<style>` tag:
\`\`\`css
:root {
    --primary: #4361ee;      /* Main brand color */
    --secondary: #3a0ca3;    /* Secondary color */
    --accent: #f72585;       /* Accent color */
    --success: #4cc9f0;      /* Success state */
}
\`\`\`

### Images
Replace image URLs in the HTML:
- Hero image: Line ~672
- Section background patterns: Search for `.unsplash.com` URLs

### Content
Edit text directly in the HTML sections:
- Hero title and subtitle: Lines ~665-667
- Section titles and descriptions: Throughout the document
- Quotes: Update `quoteArray` in JavaScript

### Fonts
Change from the default 'Segoe UI' to another system font:
\`\`\`css
body {
    font-family: 'Your Font Family', sans-serif;
}
\`\`\`

## 📝 Features Breakdown

### JavaScript Functionality

1. **Progress Bar**
   - Tracks page scroll position
   - Updates in real-time

2. **Navigation Scroll Effect**
   - Navbar styling changes on scroll
   - Smooth transitions

3. **Fade-in Animations**
   - Elements animate in as they come into view
   - Intersection Observer API

4. **Quote System**
   - 8 inspirational quotes
   - Random quote selection
   - Smooth transitions

5. **Form Validation**
   - Bootstrap validation
   - Real-time feedback
   - Success messages

6. **Smooth Scrolling**
   - Anchor link navigation
   - Built-in browser feature

## 🔒 Security

- No external API calls to untrusted sources
- Form data handling with client-side validation
- All resources loaded from trusted CDNs
- No sensitive data collection

## ♿ Accessibility

- Semantic HTML structure
- ARIA labels on interactive elements
- Alt text for all images
- Keyboard navigation support
- Color contrast compliance
- Screen reader friendly

## 📊 Performance

- Optimized image loading with `loading="lazy"`
- Minified CSS within style tag
- CDN delivery for libraries
- Smooth 60fps animations
- No render-blocking scripts

## 📄 License

This project is open source and available for personal and commercial use. Feel free to modify and distribute.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📧 Support

For questions, issues, or suggestions:
- Create an issue on GitHub
- Use the contact form on the website
- Email us directly

## 🎯 Future Enhancements

- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Blog section for articles
- [ ] Event calendar
- [ ] Donation integration
- [ ] Testimonials section
- [ ] Newsletter signup
- [ ] Video content integration

## 📊 Statistics & Analytics

Ready to integrate with:
- Google Analytics
- Vercel Analytics
- Other tracking platforms

## 🌟 Credits

- **Images**: Unsplash.com
- **Icons**: Font Awesome
- **CSS Framework**: Bootstrap 5
- **Animations**: Animate.css

## 📅 Last Updated

December 2025

---

**Made with ❤️ for cancer awareness and support**
