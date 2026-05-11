# 🎨 Portfolio Customization Guide

Complete step-by-step guide to customize this portfolio template for your own profile.

---

## 📋 Table of Contents

1. [Getting Started](#getting-started)
2. [Content Updates](#content-updates)
3. [Design Customization](#design-customization)
4. [Images & Media](#images--media)
5. [Social Links](#social-links)
6. [SEO Settings](#seo-settings)
7. [Deployment Checklist](#deployment-checklist)

---

## Getting Started

### Step 1: Fork/Clone the Repository

```bash
# Clone to your machine
git clone https://github.com/NikhilRaj-DevOps/NikhilRajNR.github.io.git

# Rename repository to your GitHub username
# <username>.github.io
```

### Step 2: Update Repository Name

1. Go to repository Settings
2. Change name to: `<your-github-username>.github.io`
3. Save changes

---

## Content Updates

### 1. Personal Information

Edit `index.html` - Replace the following:

**Find:**
```html
<h1>Nikhil Raj</h1>
<p class="lead">Results-driven Senior DevOps / SRE Engineer...</p>
```

**Replace with your info:**
```html
<h1>Your Name</h1>
<p class="lead">Your professional summary with key highlights...</p>
```

### 2. Contact Information

**Find:**
```html
<a href="mailto:nikhilrajbu@gmail.com">nikhilrajbu@gmail.com</a>
<span>•</span>
<a href="tel:+918759747230">+91 87597 47230</a>
<span>•</span>
Bangalore, India
```

**Replace with:**
```html
<a href="mailto:your.email@example.com">your.email@example.com</a>
<span>•</span>
<a href="tel:+1234567890">+1 (234) 567-890</a>
<span>•</span>
Your City, Country
```

### 3. Social Media Links

**Find:**
```html
<a href="https://github.com/NikhilRaj-DevOps" target="_blank">GitHub</a>
<a href="https://linkedin.com/in/nikhilrajnr" target="_blank">LinkedIn</a>
```

**Replace with your links:**
```html
<a href="https://github.com/your-username" target="_blank">GitHub</a>
<a href="https://linkedin.com/in/your-profile" target="_blank">LinkedIn</a>
<a href="https://twitter.com/your-handle" target="_blank">Twitter</a>
```

### 4. Professional Summary

**Find:** The About section

```html
<p>Results-driven Senior DevOps / SRE Engineer with 8+ years of experience...</p>
```

**Replace with your summary** (2-3 sentences about your experience and expertise)

### 5. Update Experience Section

Each experience card follows this structure:

```html
<div class="col-md-6">
  <div class="card experience-card">
    <div class="experience-card-head">
      <div>
        <span class="experience-role">Job Title</span>
        <p class="experience-company">Company Name | City, Country</p>
      </div>
      <span class="experience-period">Start Month Year – End Month Year</span>
    </div>
    
    <p class="experience-title">Project Name <span>Year – Year</span></p>
    <ul class="experience-list">
      <li>Key achievement or responsibility</li>
      <li>Another achievement</li>
      <li>Technology used or impact</li>
    </ul>
    <div class="experience-tools">
      <strong>Tools:</strong> Tool1, Tool2, Tool3, Tool4
    </div>
  </div>
</div>
```

**Tips:**
- Use 3-5 bullet points per role
- Focus on impact and achievements
- Include 5-8 relevant tools/technologies

### 6. Update Skills Section

Skills are organized in a grid (3 columns on desktop):

```html
<div class="col-sm-6 col-md-4">
  <div class="skill-card">
    <strong>Category Name:</strong> Skill1, Skill2, Skill3, Skill4
  </div>
</div>
```

**Suggested Categories:**
- **Languages:** Python, JavaScript, Go, etc.
- **Platforms:** AWS, Azure, GCP, etc.
- **Tools:** Docker, Kubernetes, Terraform, etc.
- **Databases:** PostgreSQL, MongoDB, etc.
- **Methodologies:** Agile, Scrum, SRE, etc.

### 7. Update Certifications

```html
<div class="col-sm-6 col-md-6">
  <div class="cert-card">
    <h3>CERT-CODE</h3>
    <p>Full Certification Name</p>
  </div>
</div>
```

### 8. Update Awards & Achievements

```html
<div class="col-sm-6 col-md-6">
  <div class="cert-card">
    <h3 style="color: #2563eb;">🏆 Award Name</h3>
    <p><strong>Organization</strong> – Project/Team</p>
    <p>Brief description of the award and why you received it.</p>
  </div>
</div>
```

### 9. Update Projects/Engagements

Each project card:

```html
<div class="col-md-6 col-lg-3">
  <div class="project-card">
    <h3>Project Name</h3>
    <p class="meta">Project Type/Category</p>
    <ul>
      <li>Key achievement or feature 1</li>
      <li>Key achievement or feature 2</li>
      <li>Impact or result</li>
      <li>Technology stack used</li>
    </ul>
  </div>
</div>
```

### 10. Update Education

```html
<div class="col-md-8 col-md-offset-2 text-center">
  <img src="images/university_logo.png" alt="University name" width="150" height="150">
  <h3>B.E. in Your Discipline</h3>
  <p>Your University Name | Year - Year</p>
</div>
```

### 11. Update Open Source Section

```html
<div class="col-md-6">
  <div class="card opensource-card">
    <h3>🔗 Your Open Source Title</h3>
    <ul>
      <li>Contribution or project 1</li>
      <li>Contribution or project 2</li>
      <li><a href="https://github.com/your-username" target="_blank">Visit my GitHub</a></li>
    </ul>
  </div>
</div>
```

---

## Design Customization

### Color Scheme

Edit `css/custom.css` to change colors:

```css
/* Primary Colors */
--primary-dark: #0f172a;      /* Dark navy */
--primary-light: #f8fafc;     /* Light white */
--accent: #38bdf8;            /* Cyan/Blue */
--accent-dark: #1d4ed8;       /* Dark blue */

/* Background Colors */
--bg-light: #f4f7fb;
--bg-white: #ffffff;
--text-dark: #102a43;
--text-gray: #475569;
```

**Common color changes:**

1. **Navigation Bar** - Find `.navbar-inverse`
2. **Hero Section** - Find `.jumbotron`
3. **Section Headers** - Find `.section-heading h2`
4. **Buttons** - Find `.btn-danger`, `.btn-default`
5. **Cards** - Find `.card`, `.experience-card`

### Font Changes

Replace in `<head>` section:

```html
<!-- Current -->
<link href="https://fonts.googleapis.com/css?family=Arvo:400,700&display=swap" rel="stylesheet">
<style>font-family: 'Arvo', sans-serif;</style>

<!-- Alternative Options -->
<!-- For professional: -->
<link href="https://fonts.googleapis.com/css?family=Poppins:400,600,700&display=swap" rel="stylesheet">

<!-- For technical: -->
<link href="https://fonts.googleapis.com/css?family=JetBrains+Mono:400,600&display=swap" rel="stylesheet">

<!-- For elegant: -->
<link href="https://fonts.googleapis.com/css?family=Playfair+Display:700&display=swap" rel="stylesheet">
```

### Spacing & Padding

Edit section padding in `css/custom.css`:

```css
.section {
  padding: 80px 0;  /* Change this value */
}

.section-heading {
  margin-bottom: 50px;  /* Change spacing */
}
```

### Card Border Radius

Increase/decrease rounded corners:

```css
.card, .experience-card, .project-card {
  border-radius: 24px;  /* Larger = more rounded */
}
```

---

## Images & Media

### Add Hero Image

1. **Prepare Image:**
   - Size: 1920×1080px minimum
   - Format: JPG or PNG
   - Size: < 500KB (compress if needed)

2. **Place in `images/` folder:**
   ```
   images/hero_image.jpg
   ```

3. **Reference in CSS:**
   ```css
   .jumbotron {
     background: linear-gradient(...), url('../images/hero_image.jpg') center / cover no-repeat;
   }
   ```

### Add University Logo

1. **Logo size:** 150×150px
2. **Name:** `University_of_[Name]_logo.png`
3. **Place in `images/` folder**
4. **Update HTML:**
   ```html
   <img src="images/your_university_logo.png" alt="University name" width="150" height="150">
   ```

### Add Favicon

1. **Create favicon:** Use [favicon.io](https://favicon.io)
2. **Generate files:** favicon.png (32×32px)
3. **Place in `images/` folder**
4. **Already referenced in HTML:**
   ```html
   <link rel="icon" type="image/png" sizes="32x32" href="images/favicon-32x32.png">
   ```

### Add Resume PDF

1. **Create/Convert Resume:**
   - Word → Export as PDF
   - Google Docs → Download as PDF
   - Name: `resume.pdf`

2. **Place in root directory:**
   ```
   NikhilRajNR.github.io/
   ├── index.html
   ├── resume.pdf
   ├── css/
   └── images/
   ```

3. **Download button already in footer** (no changes needed)

---

## Social Links

### Add More Social Networks

Find the footer contact section and add:

```html
<p>
  <a href="https://github.com/your-username" target="_blank" class="contact-link">
    <i class="fa fa-github"></i> GitHub
  </a>
  <span>•</span>
  <a href="https://linkedin.com/in/your-profile" target="_blank" class="contact-link">
    <i class="fa fa-linkedin"></i> LinkedIn
  </a>
  <span>•</span>
  <a href="https://twitter.com/your-handle" target="_blank" class="contact-link">
    <i class="fa fa-twitter"></i> Twitter
  </a>
  <span>•</span>
  <a href="https://medium.com/@your-username" target="_blank" class="contact-link">
    <i class="fa fa-medium"></i> Medium
  </a>
</p>
```

**Available Font Awesome icons:**
- `fa-github` - GitHub
- `fa-linkedin` - LinkedIn
- `fa-twitter` - Twitter
- `fa-facebook` - Facebook
- `fa-instagram` - Instagram
- `fa-medium` - Medium
- `fa-dev` - Dev.to
- `fa-youtube` - YouTube
- `fa-stack-overflow` - Stack Overflow

---

## SEO Settings

### Update Meta Tags

Find in `<head>` section:

```html
<!-- Current -->
<meta name="description" content="Current description...">
<meta name="keywords" content="DevOps, SRE, Kubernetes...">

<!-- Update to your info -->
<meta name="description" content="Your professional summary - 160 characters max">
<meta name="keywords" content="your-skill-1, your-skill-2, your-title">
```

### Update Open Graph Tags

```html
<meta property="og:title" content="Your Name | Your Title">
<meta property="og:description" content="Your professional summary">
<meta property="og:image" content="path-to-your-image.jpg">
<meta property="og:url" content="https://yourusername.github.io">
```

### Update Title Tag

```html
<title>Your Name | Your Job Title - Your Key Specialization</title>
```

**Best practice:**
- Length: 50-60 characters
- Include name + title + key skill
- Example: "John Doe | DevOps Engineer - AWS & Kubernetes Expert"

---

## Deployment Checklist

### Before Publishing

- [ ] All personal information is updated
- [ ] All social links are correct
- [ ] Resume is uploaded (resume.pdf)
- [ ] All images are in place and optimized
- [ ] Meta tags and title are updated
- [ ] All links are working (test locally)
- [ ] Mobile responsive (test on phone)
- [ ] No broken images (check console)
- [ ] All text is spell-checked
- [ ] Font sizes are readable
- [ ] Contact information is current

### Local Testing

```bash
# Start local server
python -m http.server 8000

# Visit http://localhost:8000

# Check:
# - All links work
# - Images display
# - Responsive on mobile (F12 → Toggle device toolbar)
# - No console errors
```

### Publishing

```bash
# Stage all changes
git add .

# Commit with descriptive message
git commit -m "Initial portfolio setup with personal information"

# Push to GitHub
git push origin main

# Visit https://yourusername.github.io
# Wait 1-2 minutes for deployment
```

### Post-Launch

- [ ] Verify site is live at correct URL
- [ ] Test all navigation links
- [ ] Check mobile responsiveness
- [ ] Test contact links
- [ ] Verify resume downloads
- [ ] Check social links open correctly
- [ ] Test on different browsers

---

## Quick Edit Checklist

**Minimum edits required:**
1. ✅ Name in hero section
2. ✅ Professional summary
3. ✅ Experience (at least 1-2 roles)
4. ✅ Skills (your tech stack)
5. ✅ Education
6. ✅ Email address
7. ✅ GitHub/LinkedIn links
8. ✅ Remove/add sections as needed

**Optional enhancements:**
1. ✅ Upload resume.pdf
2. ✅ Add hero background image
3. ✅ Update color scheme
4. ✅ Add projects/portfolio work
5. ✅ Add certifications
6. ✅ Add open source contributions
7. ✅ Add university logo

---

## Troubleshooting

### Issue: Changes not showing up

**Solution:**
1. Hard refresh browser: `Ctrl+Shift+R` (Windows) or `Cmd+Shift+R` (Mac)
2. Wait 2-3 minutes for GitHub Pages to rebuild
3. Check repository Settings → Pages for build status

### Issue: Images not loading

**Solution:**
1. Verify file names match exactly (case-sensitive)
2. Ensure images are in `images/` folder
3. Check file paths in HTML are correct
4. Compress images if larger than 1MB

### Issue: Styling looks off

**Solution:**
1. Clear browser cache
2. Check CSS file is loading (check Network tab)
3. Verify no syntax errors in CSS
4. Check Bootstrap CSS is loaded

### Issue: Links not working

**Solution:**
1. Verify URLs are complete (include https://)
2. Use `target="_blank"` for external links
3. Add `rel="noopener"` for security
4. Test links locally first

---

## Support Resources

- [Bootstrap 3 Docs](https://getbootstrap.com/docs/3.4/)
- [Font Awesome Icons](https://fontawesome.com/icons)
- [Google Fonts](https://fonts.google.com/)
- [GitHub Pages Help](https://docs.github.com/en/pages)
- [HTML Validator](https://validator.w3.org/)
- [CSS Validator](https://jigsaw.w3.org/css-validator/)

---

**Happy customizing! 🎉**
