# Solutions Engineer Portfolio

Professional web portfolio showcasing cloud infrastructure expertise, hybrid migrations, and enterprise-scale architecture experience.

## 🚀 Live Demo

View at: `https://yourusername.github.io/portfolio`

## 📋 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile
- **Performance**: Single-page HTML with no external dependencies (fonts loaded from Google)
- **Professional Aesthetic**: Dark theme with technical typography (JetBrains Mono + Crimson Pro)
- **Recruiter-Optimized**: Structured for technical recruiters at Netflix, Amazon, Google, etc.

## 🔧 Deployment to GitHub Pages

### Quick Setup

1. **Create a new repository**
   ```bash
   # On GitHub, create new repo named "portfolio" (or any name)
   # Initialize locally
   git init
   git add index.html README.md
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages (left sidebar)
   - Under "Source", select branch: `main`
   - Select folder: `/ (root)`
   - Click Save

3. **Your site will be live at:**
   ```
   https://yourusername.github.io/portfolio
   ```

### Custom Domain (Optional)

If you own a domain:

1. Add a `CNAME` file to repository root:
   ```bash
   echo "yourdomain.com" > CNAME
   git add CNAME
   git commit -m "Add custom domain"
   git push
   ```

2. Configure DNS with your domain provider:
   - Add A records pointing to GitHub's IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - Or add CNAME record: `yourusername.github.io`

3. In GitHub Settings → Pages, enter your custom domain

## ✏️ Customization

### Update Contact Information

Line 272-275 in `index.html`:
```html
<a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
<a href="https://github.com/yourusername" target="_blank">GitHub</a>
<a href="mailto:your.email@example.com">Email</a>
```

### Modify Stats

Lines 290-305 - Update the hero statistics:
```html
<span class="stat-number">50+</span>
<span class="stat-label">Cloud Migrations</span>
```

### Architecture Confidentiality

The current architecture diagrams show high-level component relationships without:
- Specific AWS account numbers
- Internal IP ranges beyond standard private ranges
- Proprietary business logic
- Customer-specific identifiers
- Security group rules
- IAM policies

This maintains NDA compliance while demonstrating architectural thinking.

## 🎯 Target Audience

Optimized for recruiters at:
- Netflix (Solutions Engineer roles)
- Amazon/AWS (Solutions Architect, TAM)
- Google Cloud (Customer Engineer)
- Microsoft Azure (Cloud Solution Architect)
- Enterprise SaaS companies

## 📊 Technical Highlights

- **10+ years infrastructure experience**
- **50+ cloud migrations** completed
- **130+ production locations** supported
- **45min average MTTR** for critical incidents
- **Zero-downtime migrations** using Strangler Fig pattern

## 🔒 Security & Compliance

All architecture details are:
- Genericized (no customer names)
- High-level (no implementation specifics)
- Industry-standard patterns (publicly documented)
- Focused on methodology over proprietary details

## 📝 License

This portfolio template is free to use and modify for personal use.

## 🤝 Contributing

This is a personal portfolio, but suggestions for improvements are welcome via issues.

## 📧 Contact

For opportunities or questions, reach out via the contact links on the live site.

---

**Built with**: Semantic HTML5, Modern CSS3, Zero JavaScript framework dependencies

**Fonts**: JetBrains Mono (code/technical) + Crimson Pro (body/elegance)

**Hosting**: GitHub Pages (free, reliable, fast global CDN)