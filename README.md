# TDA Architecture Website

A professional, modern HTML website for TDA Architecture - an architectural design firm.

## 📁 Project Structure

```
TDA-Website/
├── index.html              # Home page
├── projects.html           # Projects portfolio page
├── our-team.html           # Team members page
├── about-us.html           # About Us page (mission, values, why choose us)
├── our-services.html       # Services page
├── contact.html            # Contact page with form
├── styles.css              # Main stylesheet
├── images/                 # Image folder
│   └── profile-photo.jpg   # Your profile photo (add here)
└── README.md               # This file
```

## 🎨 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI** - Clean, professional design suitable for an architectural firm
- **Beautiful Logo** - Custom SVG logo integrated into the header
- **Navigation Menu** - Easy-to-use menu with dropdown for About section
- **Social Media Links** - LinkedIn, Instagram, and Facebook links in header and footer
- **Contact Form** - Interactive contact form (demo - needs backend integration)
- **Professional Content** - Comprehensive content for all pages including:
  - Mission Statement
  - Value Statement
  - Why Clients Choose Us section
  - Services overview
  - Team profiles
  - Project showcase

## 🚀 Getting Started

### 1. Open the Website
Simply open `index.html` in any web browser to view the website.

### 2. Add Your Profile Photo
- Place your profile photo in the `images/` folder
- Name it `profile-photo.jpg` (or update the filename in `our-team.html`)
- Recommended size: 400x400 pixels or larger (square format)

### 3. Customize Social Media Links
Replace the placeholder URLs in all HTML files:
- LinkedIn: `https://www.linkedin.com`
- Instagram: `https://www.instagram.com`
- Facebook: `https://www.facebook.com`

Search for these URLs in each HTML file and replace with your actual social media profile links.

### 4. Update Contact Information
Edit `contact.html` to update:
- Office address
- Phone numbers
- Email addresses
- Office hours

### 5. Customize Content
All content can be edited directly in the HTML files:
- Company description
- Mission statement
- Values
- Services
- Team member information
- Project details

## 📄 Page Overview

### Home Page (index.html)
- Hero section with call-to-action
- Introduction to TDA Architecture
- Featured projects preview
- Services preview
- Call-to-action section

### Projects Page (projects.html)
- Portfolio of 6 sample projects
- Project details with images
- Project categories/tags
- Call-to-action

### Our Team Page (our-team.html)
- Team introduction
- 6 team member profiles (including yours)
- Profile photos, roles, and bios
- Social media links for each member
- Career opportunities section

### About Us Page (about-us.html)
- Company story and history
- Mission statement
- Core values (6 values)
- Why clients choose us (6 reasons)
- Statistics section
- Call-to-action

### Our Services Page (our-services.html)
- 6 comprehensive service offerings:
  - Commercial Architecture
  - Residential Design
  - Interior Design
  - Sustainable Design
  - Project Management
  - Consultation Services
- Process timeline (6 steps)
- Call-to-action

### Contact Page (contact.html)
- Contact information (address, phone, email, hours)
- Contact form with validation
- Social media links
- Map placeholder (instructions to add Google Maps)

## 🎨 Customization Tips

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c3e50;    /* Main dark color */
    --secondary-color: #3498db;  /* Accent blue color */
    --accent-color: #e74c3c;     /* Secondary accent */
}
```

### Changing Images
All images are currently using Unsplash URLs. To replace:
1. Download or create your own images
2. Save them in the `images/` folder
3. Update the `background-image` or `src` attributes in the HTML files

### Updating the Logo
The logo is an inline SVG in the header. You can:
- Replace it with a PNG/JPG image
- Modify the SVG code to create a different design
- Use a logo generator to create a custom logo

## 📱 Social Media Integration

The website includes social media links in:
- Header navigation (all pages)
- Footer (all pages)
- Team member profiles (our-team.html)
- Contact page (contact.html)

Remember to update all instances with your actual social media URLs.

## 💡 Making the Contact Form Functional

The contact form currently shows a demo alert. To make it functional:

**Option 1: Use a Form Service**
- FormSpree (https://formspree.io/)
- Netlify Forms (if hosting on Netlify)
- Google Forms integration

**Option 2: Backend Integration**
- Set up a backend server (Node.js, PHP, Python, etc.)
- Create an API endpoint to handle form submissions
- Update the form's action attribute and JavaScript

**Option 3: Email Service**
- Use EmailJS (https://www.emailjs.com/)
- Integrates directly with JavaScript, no backend needed

## 🌐 Hosting the Website

You can host this website on:
- **GitHub Pages** (Free)
- **Netlify** (Free)
- **Vercel** (Free)
- **Traditional Web Hosting** (Paid)
- **Your own server**

Simply upload all files to your hosting provider.

## 📝 Browser Compatibility

This website works on:
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📧 Support

For questions or assistance customizing the website, refer to:
- HTML/CSS documentation: [MDN Web Docs](https://developer.mozilla.org/)
- Font Awesome icons: [Font Awesome](https://fontawesome.com/)

## 📄 License

This website template is provided as-is for TDA Architecture. Feel free to modify and use it as needed.

---

**Built with ❤️ for TDA Architecture**

*Last Updated: April 2026*
