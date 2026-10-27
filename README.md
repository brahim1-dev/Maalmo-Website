# Maalmo - Full Stack AI Engineer Program

## Look here https://maalmo-website.netlify.app/

> A modern, responsive website for Maalmo, a comprehensive Full Stack AI Engineer training program designed to help developers master AI-assisted development.

![Maalmo Banner](./images/home.jpg)

## 🎯 Overview

Maalmo is an innovative educational platform that offers:
- **Full Stack AI Engineering Courses** - Learn to build with AI assistance
- **Mentorship Programs** - Get guided by experienced professionals
- **Career Development** - Unlock your potential and advance your career
- **Community** - Join a vibrant community of learners and builders

The only Somali-language program teaching AI-assisted development.

## ✨ Features

- 📱 **Fully Responsive Design** - Works beautifully on all devices (mobile, tablet, desktop)
- 🎨 **Modern UI/UX** - Built with Bootstrap 5 for a professional look
- 💬 **Contact Form** - Integrated with Netlify Forms for easy message collection
- 🔗 **Smooth Navigation** - Single-page application with smooth scrolling
- 📚 **Blog Section** - Articles on AI, Data Science, DevOps, and more
- 🎓 **Mentorship Details** - Clear information about mentee responsibilities
- 💰 **Service Pricing** - Multiple course tiers with pricing information

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required - it's a static HTML/CSS/JS website

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/maalmo.git
   cd maalmo
   ```

2. **Open in your browser**
   - Simply open `index.html` in your web browser, or
   - Use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Or using Python 2
     python -m SimpleHTTPServer 8000
     
     # Or using Node.js (if you have http-server installed)
     npx http-server
     ```

3. **View the site**
   - Open `http://localhost:8000` in your browser

## 📁 Project Structure

```
maalmo/
├── index.html          # Main HTML file
├── images/             # Images directory
│   ├── logo1.png
│   ├── home.jpg
│   ├── abouta.png
│   ├── mentor1.png
│   ├── blog-2.jpg
│   └── ...
└── README.md           # This file
```

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **Bootstrap 5** - Responsive CSS framework
- **Bootstrap Icons** - SVG icon library
- **Vanilla JavaScript** - Interactivity via Bootstrap
- **Netlify Forms** - Form handling and submissions

## 📝 Sections

### Navigation Bar
- Quick links to all sections
- Login/Sign Up buttons
- Mobile responsive hamburger menu

### Home
- Hero section with call-to-action
- Key value propositions (Services, Free Consultation, Support)

### About
- Mission and goals of Maalmo
- Key achievements and commitments

### Services
- 9 different course offerings
- Pricing tiers ($19.99 - $49.99)
- Feature highlights for each course

### Mentorship
- Mentee benefits and opportunities
- Clear responsibilities for participants
- Call-to-action for becoming a mentee

### Blog
- Latest articles and tutorials
- Topics: AI, Data Science, DevOps, Career Growth
- Search and filter functionality

### Contact
- Multiple contact methods (Email, WhatsApp, Location, Hours)
- Contact form for inquiries
- Netlify form integration

## 📧 Contact Information

- **Email:** info@maalmo.com
- **WhatsApp:** +252 61 1434258
- **Location:** Mogadishu, Somalia
- **Hours:** Mon–Fri · 9AM–6PM EAT (East Africa Time)

## 🌐 Deployment to Netlify

### Method 1: Using Git (Recommended)

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit: Maalmo website"
   git push origin main
   ```

2. **Connect to Netlify**
   - Go to [netlify.com](https://netlify.com)
   - Click "New site from Git"
   - Select your GitHub repository
   - Configure build settings:
     - **Build command:** (leave empty - it's static HTML)
     - **Publish directory:** . (current directory)
   - Click "Deploy site"

### Method 2: Direct Upload

1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag and drop the entire `maalmo` folder
3. Your site will be deployed instantly!

### Method 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```

## 🔄 Netlify Form Configuration

The contact form is already configured for Netlify. When deployed:
1. Netlify automatically detects the form with `data-netlify="true"`
2. Form submissions appear in your Netlify dashboard under "Forms"
3. You can set up email notifications for new submissions

## 🎨 Customization

To customize the site:

- **Colors:** Edit the CSS in the `<style>` tag (currently using green #198754)
- **Content:** Edit text directly in the HTML sections
- **Images:** Replace images in the `images/` folder
- **Logo:** Update `./images/logo1.png`
- **Social Links:** Update social media links in the footer

## 📱 Responsive Breakpoints

The site is fully responsive with Bootstrap's breakpoints:
- **Extra small:** < 576px
- **Small:** ≥ 576px
- **Medium:** ≥ 768px
- **Large:** ≥ 992px
- **Extra large:** ≥ 1200px

## ✅ Performance Considerations

- Uses CDN for Bootstrap and Bootstrap Icons
- Minimal custom CSS for fast loading
- Optimized images recommended in `images/` folder
- Consider lazy loading images for better performance

## 📄 License

This project is free to use and modify for personal and commercial purposes.

## 🤝 Contributing

To contribute improvements:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 👤 Author

**Maalmo Team**
- 🔗 [GitHub](https://github.com/brahim1-dev)
- 📧 Email: info@maalmo.com

## 🎯 Future Enhancements

- [ ] Add authentication system for course enrollment
- [ ] Implement blog post management
- [ ] Add payment integration for course purchases
- [ ] Create student dashboard
- [ ] Add testimonials section
- [ ] Implement dark mode
- [ ] Add multi-language support

## 📞 Support

For questions or support, reach out:
- **WhatsApp:** +252 61 1434258
- **Email:** info@maalmo.com
- **Location:** Mogadishu, Somalia

---

**Made with ❤️ in Somalia**

© 2026 Maalmo. All rights reserved.
