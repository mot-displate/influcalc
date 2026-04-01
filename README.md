# Displate Influencer CPA Calculator

Internal tool for calculating influencer campaign CPA (Cost Per Acquisition) with various deal structures and revenue models.

## 🚀 Deployed at
**https://mot-displate.github.io/influcalc/**

---

## Features

- Calculate CPA for different influencer deal types
- Support for flat fees, CPA deals, and hybrid models
- Revenue tracking with standard vs. LE/ULE product lines
- Real-time calculations as you type
- Clean, professional interface

---

## Setup

This repo uses GitHub Actions to automatically deploy to GitHub Pages.

### First-Time Setup:

1. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Source: Select **"GitHub Actions"**
   - Save

2. **Enable Workflow Permissions:**
   - Go to Settings → Actions → General
   - Scroll to "Workflow permissions"
   - Select **"Read and write permissions"**
   - Check "Allow GitHub Actions to create and approve pull requests"
   - Save

3. **Push changes** - the site will auto-deploy in ~30 seconds

---

## Making Updates

Just edit `index.html` and commit:

```bash
git add index.html
git commit -m "Update calculator"
git push
```

Site updates automatically in ~30 seconds.

---

## File Structure

```
influcalc/
├── index.html                    # The calculator app
├── .github/
│   └── workflows/
│       └── deploy.yml            # Auto-deployment
└── README.md                     # This file
```

---

**Maintained by:** Nicola @ Displate  
**Last Updated:** 2026-04
