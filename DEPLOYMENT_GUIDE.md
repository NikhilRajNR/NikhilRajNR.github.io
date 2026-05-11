# 🚀 GitHub Pages Deployment Guide

Step-by-step guide to deploy your portfolio to GitHub Pages.

---

## Prerequisites

✅ GitHub account
✅ Git installed on your machine
✅ Portfolio files ready
✅ Repository named `<username>.github.io`

---

## Deployment Steps

### Step 1: Create GitHub Repository

1. Go to [github.com](https://github.com)
2. Click "New repository"
3. **Repository name:** `<your-github-username>.github.io`
   - Example: `john-doe.github.io`
4. **Description:** "Professional DevOps Portfolio"
5. Choose **Public** repository
6. Click "Create repository"

### Step 2: Clone Repository Locally

```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-username>.github.io.git

# Navigate to folder
cd <your-username>.github.io
```

### Step 3: Add Portfolio Files

Copy all portfolio files to your local repository:

```yaml
📁 your-username.github.io/
├── 📄 index.html
├── 📄 resume.pdf (optional)
├── 📄 README.md
├── 📄 CUSTOMIZATION_GUIDE.md
├── 📁 css/
│   ├── bootstrap.min.css
│   ├── custom.css
│   └── ...
├── 📁 js/
│   ├── bootstrap.min.js
│   └── ...
├── 📁 images/
│   ├── hero_image.jpg
│   ├── favicon-32x32.png
│   └── ...
└── 📁 fonts/
    └── font-awesome/
        └── ...
```

### Step 4: Stage and Commit Changes

```bash
# Add all files
git add .

# Commit changes
git commit -m "Initial portfolio setup"

# View status
git status
```

### Step 5: Push to GitHub

```bash
# Push to main branch
git push -u origin main

# If main branch doesn't exist, Git will create it
# After first push, use: git push origin main
```

### Step 6: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Click **Save**

### Step 7: Access Your Portfolio

Your portfolio will be available at:

```htm
https://<your-github-username>.github.io
```

**Example:**

```htm
https://john-doe.github.io
```

⏱️ **Note:** It may take 1-3 minutes for GitHub to build and deploy your site.

---

## Continuous Updates

### Make Local Changes

```bash
# Edit files locally
# Update index.html, CSS, or content

# Check what changed
git status

# View specific changes
git diff index.html
```

### Commit and Push Changes

```bash
# Stage changed files
git add .

# Commit with descriptive message
git commit -m "Update experience section with new role"

# Push to GitHub
git push origin main
```

Changes will appear on your live website within 1-2 minutes!

### Common Update Commands

```bash
# Add specific file
git add index.html

# Add all changes
git add .

# Commit
git commit -m "Your message"

# Push
git push origin main

# View commit history
git log --oneline
```

---

## Custom Domain (Optional)

### Step 1: Purchase Domain

- Buy domain from: GoDaddy, Namecheap, Google Domains, etc.
- Example domain: `yourname.dev`, `yourname.io`, etc.

### Step 2: Configure DNS Records

Add these DNS records at your registrar:

**For apex domain (yourname.com):**

```yaml
Type: A
Name: @
Value: 185.199.108.153
```

Add all four:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

**For www subdomain (<www.yourname.com>):**

```yaml
Type: CNAME
Name: www
Value: <your-github-username>.github.io
```

### Step 3: Update GitHub Pages Settings

1. Go to repository Settings → Pages
2. Scroll to **Custom domain**
3. Enter your domain name: `yourname.com`
4. Click **Save**
5. GitHub will verify and enable HTTPS

**Note:** DNS propagation takes 24-48 hours

---

## Troubleshooting Deployment

### Issue: Site not showing up

**Solution:**

1. Verify repository name is correct: `<username>.github.io`
2. Check repository is **Public** (not Private)
3. Go to Settings → Pages and verify source is set
4. Check for build errors in repository Actions tab
5. Wait 5-10 minutes and try again
6. Try hard refresh: `Ctrl+Shift+R`

### Issue: Old content still showing

**Solution:**

1. Hard refresh browser: `Ctrl+Shift+R`
2. Clear browser cache
3. Try in incognito/private window
4. Verify your commit was pushed with `git log`

### Issue: Assets (CSS/images) not loading

**Solution:**

1. Check all file paths are relative (not absolute)
2. Verify file names match exactly (case-sensitive)
3. Ensure files are committed and pushed
4. Check browser console for 404 errors

### Issue: 404 error on pages

**Solution:**

1. Verify `index.html` is in repository root
2. GitHub Pages only serves static HTML (no server-side files)
3. All links should point to `.html` files
4. For single-page app, use `index.html` only

### Issue: HTTPS not working

**Solution:**

1. Give GitHub 24 hours to enable HTTPS
2. Make sure custom domain is set correctly
3. Try clearing cache and browser cookies
4. Verify DNS settings are correct

---

## Check Deployment Status

### View Build Status

1. Go to repository
2. Click **Actions** tab
3. See deployment history and any errors

### Enable GitHub Pages Status

Repository → Settings → Pages → Check the status indicator

### View Live Site Details

1. Go to Settings → Pages
2. See your site URL
3. Verify source branch and folder
4. Check custom domain status

---

## Git Commands Reference

### Basic Operations

```bash
# Clone repository
git clone https://github.com/<user>/<repo>.git

# Check status
git status

# See what changed
git diff

# Stage all changes
git add .

# Stage specific file
git add index.html

# Commit changes
git commit -m "Update message"

# Push to GitHub
git push origin main

# Pull latest changes
git pull origin main
```

### View History

```bash
# See recent commits
git log --oneline

# See commits for specific file
git log index.html

# See who changed a line
git blame index.html
```

### Undo Changes

```bash
# Undo unstaged changes
git checkout index.html

# Undo staged changes
git reset index.html

# Undo last commit (keep changes)
git reset --soft HEAD~1

# Undo last commit (discard changes)
git reset --hard HEAD~1
```

---

## Performance Tips

### Optimize for Faster Deployment

1. **Compress images:**
   - Hero image: < 500KB
   - Use PNG or JPG
   - Use tools like TinyPNG or ImageOptim

2. **Minify CSS/JS:**
   - Remove unnecessary whitespace
   - Use minifiers: cssminifier.com, jscompress.com

3. **Use CDN for libraries:**
   - Bootstrap, jQuery, Font Awesome
   - Already done in this template

4. **Lazy load images:**
   - Add `loading="lazy"` attribute
   - Defer non-critical images

5. **Reduce redirects:**
   - Use direct links
   - Avoid unnecessary redirects

---

## Security Best Practices

✅ **HTTPS:** GitHub Pages provides free HTTPS
✅ **No secrets:** Never commit API keys, tokens, or passwords
✅ **Attribution:** Give credit for any code used
✅ **Links:** Use `rel="noopener"` for external links
✅ **Data:** Don't collect personal data without consent

---

## Monitoring Your Site

### View Analytics (Optional)

Add Google Analytics:

1. Create account at [analytics.google.com](https://analytics.google.com)
2. Get tracking ID
3. Add to `index.html` in `<head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Monitor Uptime

Services to check if site is up:

- Uptime Robot (uptimerobot.com)
- Statuspage (statuspage.io)
- Better Uptime (betteruptime.com)

---

## Collaboration

### Working with Team Members

```bash
# Create a branch for new features
git checkout -b feature/add-blog-section

# Make changes, commit
git add .
git commit -m "Add blog section"

# Push branch
git push origin feature/add-blog-section

# Create Pull Request on GitHub for review
# Merge after approval
```

---

## Backup & Version Control

### Create Backups

```bash
# Clone to backup location
git clone https://github.com/<user>/<repo>.git backup-folder

# Archive current version
git archive main --format=zip > portfolio-backup.zip
```

### Version Tags

```bash
# Create version tag
git tag -a v1.0 -m "Initial portfolio launch"

# Push tags
git push origin --tags

# View all tags
git tag -l
```

---

## Updating Repository

### Pull Latest Changes

```bash
# Get updates from remote
git pull origin main

# If conflicts occur, resolve them and:
git add .
git commit -m "Merge conflicts resolved"
git push origin main
```

### Sync Fork

If you forked this repository:

```bash
# Add upstream remote
git remote add upstream https://github.com/NikhilRaj-DevOps/NikhilRajNR.github.io.git

# Fetch updates
git fetch upstream

# Merge updates
git merge upstream/main

# Push to your fork
git push origin main
```

---

## Resources

- [GitHub Pages Docs](https://pages.github.com/)
- [GitHub Docs](https://docs.github.com/)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Desktop](https://desktop.github.com/) - GUI alternative to Git CLI

---

## Quick Start Summary

```bash
# 1. Clone repository
git clone https://github.com/<username>/<username>.github.io.git
cd <username>.github.io

# 2. Edit portfolio files
# Update index.html, CSS, images, etc.

# 3. Test locally
python -m http.server 8000
# Visit http://localhost:8000

# 4. Push to GitHub
git add .
git commit -m "Update portfolio"
git push origin main

# 5. Access at:
# https://<username>.github.io
```

---

### Your portfolio is now live! 🎉
