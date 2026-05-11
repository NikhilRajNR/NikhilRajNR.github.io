# 🚀 Nikhil Raj - Senior DevOps/SRE Engineer Portfolio

Professional portfolio website for **Nikhil Raj**, a Senior DevOps Engineer with **8+ years of experience** in CI/CD, Kubernetes, cloud infrastructure, and observability across Azure, GCP, and AWS.

**🌐 Live Portfolio:** [https://nikhilrajnr.github.io](https://nikhilrajnr.github.io)

---

## 📋 Table of Contents

- [Portfolio Features](#portfolio-features)
- [Tech Stack](#tech-stack)
- [Setup & Deployment](#setup--deployment)
- [Customization Guide](#customization-guide)
- [Sections Overview](#sections-overview)
- [Adding Resume](#adding-resume)
- [Deployment to GitHub Pages](#deployment-to-github-pages)
- [Performance & SEO](#performance--seo)
- [Contributing](#contributing)

---

## 🎯 Portfolio Features

✅ **Professional Design** - Modern, responsive, and visually appealing layout
✅ **Mobile Optimized** - Fully responsive on all devices
✅ **Fast Loading** - Optimized CSS and minimal JavaScript
✅ **SEO Friendly** - Meta tags, structured data, and semantic HTML
✅ **Dark Mode Ready** - Clean typography with high contrast colors
✅ **Experience Showcase** - Detailed work history with technologies used
✅ **Skills Breakdown** - Organized by categories (CI/CD, Containers, Cloud, etc.)
✅ **Project Highlights** - Featured engagements with key achievements
✅ **Certifications** - Display of professional credentials
✅ **Open Source Section** - GitHub contributions and community engagement
✅ **Contact Integration** - Email, phone, and social links
✅ **Resume Download** - One-click PDF resume download

---

## 🛠 Tech Stack

- **HTML5** - Semantic markup and SEO optimization
- **CSS3** - Modern styling with gradients and flexbox/grid
- **JavaScript** - Minimal vanilla JS for interactivity
- **Bootstrap 3** - Responsive grid system
- **Font Awesome** - Icon library
- **Google Fonts** - Professional typography (Arvo)
- **GitHub Pages** - Free hosting platform

---

## 🚀 Setup & Deployment

### Prerequisites

- Git installed on your system
- GitHub account
- Text editor or IDE (VS Code recommended)

### Local Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/NikhilRaj-DevOps/NikhilRajNR.github.io.git
   cd NikhilRajNR.github.io
   ```

2. **Preview locally** (optional):

   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Or using Python 2
   python -m SimpleHTTPServer 8000
   
   # Or using Node.js (if http-server is installed)
   http-server
   ```

   Then visit: `http://localhost:8000`

3. **Customize the portfolio** - See [Customization Guide](#customization-guide)

4. **Commit and push changes:**

   ```bash
   git add .
   git commit -m "Update portfolio with customizations"
   git push origin main
   ```

### Deployment to GitHub Pages

1. **Ensure correct repository name:**
   - Repository must be named: `<username>.github.io`
   - For this portfolio: `NikhilRajNR.github.io`

2. **Configure GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: Select `main` branch
   - Save changes

3. **Access your portfolio:**
   - Your site will be available at: `https://<username>.github.io`
   - Changes appear within 1-2 minutes

---

## 📝 Customization Guide

### 1. Update Basic Information

Edit `index.html` and update:

```html
<!-- Hero Section -->
<span class="eyebrow">Your Title Here</span>
<h1>Your Name</h1>
<p class="lead">Your professional summary...</p>

<!-- Contact Information -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="tel:+1234567890">+1 (234) 567-890</a>
```

### 2. Update Social Links

```html
<!-- Navigation Footer -->
<a href="https://github.com/your-username" target="_blank">GitHub</a>
<a href="https://linkedin.com/in/your-profile" target="_blank">LinkedIn</a>
<a href="https://twitter.com/your-handle" target="_blank">Twitter</a>
```

### 3. Update Experience Section

Add/edit experience cards:

```html
<div class="col-md-6">
  <div class="card experience-card">
    <div class="experience-card-head">
      <div>
        <span class="experience-role">Your Job Title</span>
        <p class="experience-company">Company Name | City, Country</p>
      </div>
      <span class="experience-period">Month Year – Present</span>
    </div>
    <p class="experience-title">Project Name <span>Year – Year</span></p>
    <ul class="experience-list">
      <li>Achievement or responsibility 1</li>
      <li>Achievement or responsibility 2</li>
    </ul>
    <div class="experience-tools"><strong>Tools:</strong> Tool1, Tool2, Tool3</div>
  </div>
</div>
```

### 4. Update Skills

Edit the Skills section (grid layout):

```html
<div class="col-sm-6 col-md-4">
  <div class="skill-card"><strong>Category:</strong> Skill1, Skill2, Skill3</div>
</div>
```

### 5. Update Projects

Modify the project cards:

```html
<div class="col-md-6 col-lg-3">
  <div class="project-card">
    <h3>Project Name</h3>
    <p class="meta">Project Category/Type</p>
    <ul>
      <li>Key achievement 1</li>
      <li>Key achievement 2</li>
    </ul>
  </div>
</div>
```

### 6. Update Education

```html
<img src="images/your-university-logo.png" alt="University name" width="150" height="150">
<h3>Your Degree Name</h3>
<p>University Name | Year - Year</p>
```

### 7. Update Certifications

```html
<div class="col-sm-6 col-md-6">
  <div class="cert-card">
    <h3>Certification Code</h3>
    <p>Certification Name</p>
  </div>
</div>
```

---

## 📂 Sections Overview

### 1. Hero/Header Section

- Eye-catching introduction
- Professional summary
- Call-to-action buttons
- Quick links to experience and contact

### 2. About/Professional Summary

- Career overview
- Key highlights and expertise
- Quick facts about experience

### 3. Experience

- Detailed work history
- Projects worked on within roles
- Technologies and tools used
- Key achievements and responsibilities

### 4. Core Skills

- Organized by categories
- CI/CD & DevOps tools
- Container & orchestration platforms
- Cloud services
- Infrastructure as Code
- Programming languages
- Monitoring tools
- Databases
- Methodologies

### 5. Certifications & Awards

- Professional certifications
- Industry recognition
- Achievement awards

### 6. Selected Engagements (Projects)

- Featured projects with highlights
- Key technical implementations
- Impact and results

### 7. Open Source & Community

- GitHub contributions
- Community involvement
- Mentoring and technical writing
- Links to repositories

### 8. Education

- Degree information
- University name
- Graduation year
- University logo

### 9. Contact & Footer

- Email address
- Phone number
- Social media links
- Resume download
- Last updated date

---

## 📄 Adding Resume

### Option 1: PDF Resume

1. **Create/Convert Resume to PDF**
   - Use Microsoft Word, Google Docs, or Canva
   - Export as PDF named `resume.pdf`

2. **Place in repository root:**

   ```yaml
   NikhilRajNR.github.io/
   ├── index.html
   ├── resume.pdf
   ├── css/
   ├── js/
   └── images/
   ```

3. **Download link in footer:**

   ```html
   <a href="resume.pdf" download class="btn btn-sm btn-danger">
     <i class="fa fa-download"></i> PDF Resume
   </a>
   ```

### Option 2: Resume Content in HTML

Add a dedicated resume section to `index.html`:

```html
<section id="Resume" class="section section-resume bg-light">
  <div class="container">
    <h2>Resume/CV</h2>
    <!-- Resume content here -->
  </div>
</section>
```

---

## 🌐 Deployment to GitHub Pages

### Initial Setup (One-time)

1. **Repository name must be:** `<username>.github.io`

2. **Push code to main branch:**

   ```bash
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Settings → Pages → Source: main branch

### Continuous Updates

Every time you make changes:

```bash
git add .
git commit -m "Update portfolio content"
git push origin main
```

Changes go live within 1-2 minutes.

### Custom Domain (Optional)

1. **Buy a domain** from registrar (GoDaddy, Namecheap, etc.)
2. **Configure DNS:**
   - Add CNAME record pointing to `username.github.io`
3. **GitHub Settings:**
   - Settings → Pages → Custom domain
   - Enter your domain name

---

## ⚡ Performance & SEO

### SEO Optimization

✅ **Meta Tags:**

- Title tag (60 characters)
- Description meta tag (160 characters)
- Keywords meta tag
- Author meta tag
- Viewport meta tag for mobile

✅ **Open Graph Tags:**

- og:title, og:description, og:image, og:url

✅ **Semantic HTML:**

- Proper heading hierarchy (h1, h2, h3)
- Semantic elements (header, nav, main, footer)
- Structured data markup

### Performance Tips

1. **Optimize Images:**
   - Compress hero image
   - Use WebP format where possible
   - Add alt text to all images

2. **Minimize CSS/JS:**
   - Minify custom CSS
   - Remove unused Bootstrap components

3. **Lazy Loading:**
   - Defer non-critical JavaScript
   - Use native lazy loading for images

4. **Caching:**
   - GitHub Pages handles automatic caching
   - Use `.gitignore` for unnecessary files

---

## 🔍 SEO Checklist

- [ ] Meta description is compelling (under 160 characters)
- [ ] Keywords in title and description
- [ ] All images have descriptive alt text
- [ ] Heading hierarchy is correct (h1 → h2 → h3)
- [ ] Internal links are working
- [ ] External links have rel="noopener"
- [ ] Mobile responsiveness is tested
- [ ] Page loads in under 3 seconds
- [ ] Favicon is set
- [ ] Social media links are present
- [ ] Contact information is visible

---

## 📱 Responsive Design

Portfolio is fully responsive and tested on:

- ✅ Desktop (1920px, 1440px, 1024px)
- ✅ Tablet (768px)
- ✅ Mobile (375px, 414px, 540px)

Media queries handle:

- Font sizes
- Padding/margins
- Grid layouts
- Navigation menu

---

## 🔐 Privacy & Security

- No external tracking scripts
- No cookies or user data collection
- HTTPS enabled by default on GitHub Pages
- Safe social media links (target="_blank", rel="noopener")

---

## 📧 Contact & Support

**Email:** <nikhilrajbu@gmail.com>
**Phone:** +91 87597 47230
**GitHub:** <https://github.com/NikhilRaj-DevOps>
**LinkedIn:** <https://linkedin.com/in/nikhilrajnr>

---

## 📜 License

This portfolio template is free to use and modify. Feel free to fork and customize for your own use.

---

## 🙌 Contributing

Have improvements or suggestions? Feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

## 📚 Resources

- [GitHub Pages Documentation](https://pages.github.com/)
- [Bootstrap 3 Documentation](https://getbootstrap.com/docs/3.4/)
- [Font Awesome Icons](https://fontawesome.com/icons)
- [Google Fonts](https://fonts.google.com/)
- [SEO Starter Guide](https://developers.google.com/search/docs/beginner/seo-starter-guide)
- [Web Development Best Practices](https://web.dev/vitals/)

---

## ✨ Last Updated

**May 2026** - Portfolio version 2.0 with enhanced design and new sections

---

### Created with ❤️ by Nikhil Raj
