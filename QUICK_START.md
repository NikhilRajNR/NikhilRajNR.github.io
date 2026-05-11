# ⚡ Quick Start Guide

Get your portfolio live in **5 minutes**!

---

## Step 1: Setup (1 minute)

```bash
# Clone this repository
git clone https://github.com/NikhilRaj-DevOps/NikhilRajNR.github.io.git
cd NikhilRajNR.github.io

# Or fork it on GitHub and clone your fork
git clone https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
```

---

## Step 2: Customize (3 minutes)

Open `index.html` in your text editor and find/replace:

### Find This → Replace With Your Info

```md
Nikhil Raj                          → Your Name
Senior DevOps / SRE Engineer        → Your Job Title
nikhilrajbu@gmail.com               → your.email@example.com
+918759747230                       → Your Phone
https://github.com/NikhilRaj-DevOps → Your GitHub Profile
https://linkedin.com/in/nikhilrajnr → Your LinkedIn Profile
```

**What to update:**

- [ ] Name (line 62)
- [ ] Job Title (line 60, 70)
- [ ] Professional Summary (line 63)
- [ ] Email (line 66, 379)
- [ ] Phone (line 67, 380)
- [ ] GitHub link (line 71, 385)
- [ ] LinkedIn link (line 72, 386)
- [ ] Experience section (lines 120-180)
- [ ] Skills section (lines 210-260)

---

## Step 3: Deploy (1 minute)

```bash
# Stage changes
git add .

# Commit
git commit -m "Update portfolio with my information"

# Push to GitHub
git push origin main
```

---

## Step 4: Go Live

Visit: `https://YOUR-USERNAME.github.io`

✨ **Your portfolio is now live!**

---

## 📱 Test Locally (Optional)

Before pushing to GitHub:

```bash
# Start local server
python -m http.server 8000

# Open browser to
http://localhost:8000

# Check:
# ✓ Links work
# ✓ Images display
# ✓ Mobile view (press F12)
# ✓ No console errors
```

---

## 📋 Essential Updates

### Minimum Required Changes

1. **Your Name** in hero section
2. **Your Title** in header
3. **Your Email**
4. **Your GitHub/LinkedIn**
5. **At least 1 experience entry**
6. **Your skills**

### Optional Enhancements

- [ ] Upload `resume.pdf`
- [ ] Add hero background image
- [ ] Update all experience roles
- [ ] Add projects/portfolio
- [ ] Update education
- [ ] Add certifications

---

## 📂 File Structure

```yaml
📁 repository/
├── 📄 index.html           ← Main page (EDIT THIS)
├── 📄 resume.pdf           ← Your resume (UPLOAD)
├── 📄 README.md            ← Portfolio info
├── 📁 css/
│   └── custom.css          ← Styling (optional edits)
├── 📁 js/
│   └── bootstrap.min.js
└── 📁 images/
    ├── hero_image.jpg      ← Background (upload yours)
    ├── favicon-32x32.png   ← Icon
    └── University_logo.png ← Education logo
```

---

## 🎯 Key Sections to Update

### 1. Hero Section

```html
<h1>Your Name</h1>
<p class="lead">Your professional summary here</p>
<a href="mailto:your.email@example.com">your.email@example.com</a>
```

### 2. Experience

```html
<span class="experience-role">Your Job Title</span>
<p class="experience-company">Company Name | City</p>
<span class="experience-period">Month Year – Present</span>
<ul class="experience-list">
  <li>Your achievement or responsibility</li>
</ul>
```

### 3. Skills

```html
<div class="skill-card">
  <strong>Your Category:</strong> Skill1, Skill2, Skill3
</div>
```

### 4. Education

```html
<h3>Your Degree Name</h3>
<p>Your University Name | 2020 - 2024</p>
```

---

## 🚀 Common Updates

### Change Hero Title

Find: `<span class="eyebrow">Senior DevOps / SRE Engineer</span>`
Replace: `<span class="eyebrow">Your Title</span>`

### Change Background Color

File: `css/custom.css`
Find: `background: linear-gradient(180deg, #f4f7fb 0%, #e8eef6 100%);`
(Change hex colors)

### Change Button Color

File: `css/custom.css`
Find: `.btn-danger` color values
(Update to your preferred color)

---

## 🔗 Where to Find Things

| What | Where | Line |
| ------ | ------- | ------ |
| Name | index.html | 62 |
| Title | index.html | 60, 70 |
| Summary | index.html | 63, 78-80 |
| Email | index.html | 66, 379 |
| Phone | index.html | 67, 380 |
| GitHub | index.html | 71, 385 |
| LinkedIn | index.html | 72, 386 |
| Experience | index.html | 110-180 |
| Skills | index.html | 200-260 |
| Education | index.html | 340-350 |

---

## ⚠️ Common Mistakes

❌ **Don't:**

- Change HTML structure (breaks layout)
- Remove CSS classes (breaks styling)
- Push `.git` or `node_modules`
- Commit large images > 1MB
- Use absolute URLs

✅ **Do:**

- Use relative URLs (`images/logo.png`)
- Keep HTML structure intact
- Compress images before uploading
- Test locally before pushing
- Use descriptive commit messages

---

## 🛠️ Troubleshooting

### Site not showing up?

1. Repository named `<username>.github.io`?
2. Repository set to PUBLIC?
3. Settings → Pages → Source set to `main`?
4. Wait 2-3 minutes
5. Hard refresh: `Ctrl+Shift+R`

### Old content still showing?

1. Hard refresh: `Ctrl+Shift+R`
2. Wait 1-2 minutes for rebuild
3. Check you pushed with: `git log`
4. Try incognito window

### Links not working?

1. Check URLs start with `https://`
2. Remove spaces from URLs
3. Test in incognito window
4. Check browser console for errors

---

## 📞 Get Help

### Resources

- [GitHub Pages Guide](https://pages.github.com/)
- [Git Basics](https://rogerdudler.github.io/git-guide/)
- [Bootstrap Docs](https://getbootstrap.com/docs/3.4/)

### Read More

- See `CUSTOMIZATION_GUIDE.md` for detailed instructions
- See `DEPLOYMENT_GUIDE.md` for deployment help
- See `CONFIGURATION.md` for all settings

---

## ✅ Launch Checklist

Before going live:

- [ ] Name is updated
- [ ] Email is correct
- [ ] Social links work
- [ ] No broken links
- [ ] Images load
- [ ] Mobile looks good
- [ ] No console errors
- [ ] All text is correct

---

## 🎉 You're Done

```bash
# Your portfolio is live at:
https://YOUR-USERNAME.github.io
```

**Congratulations! Your professional portfolio is now online.**

Share with:

- LinkedIn profile
- Job applications
- Resume
- Business cards
- Email signature

---

## Next Steps

1. **Share your portfolio** in your job applications
2. **Update resume.pdf** when needed
3. **Keep content fresh** with regular updates
4. **Add new projects** as you complete them
5. **Monitor feedback** from recruiters and peers

---

## Pro Tips

💡 **Add resume:** Upload `resume.pdf` to root folder
💡 **Custom domain:** Set up DNS to point to your GitHub Pages URL
💡 **Analytics:** Add Google Analytics for visitor tracking
💡 **Search:** Submit to Google Search Console for better SEO
💡 **Backup:** Always commit changes to Git

---

**Questions? Check the other guide files!**

- 📖 Full customization → `CUSTOMIZATION_GUIDE.md`
- 🚀 Deployment help → `DEPLOYMENT_GUIDE.md`  
- ⚙️ All settings → `CONFIGURATION.md`

---

### Created for DevOps Professionals | 2026
