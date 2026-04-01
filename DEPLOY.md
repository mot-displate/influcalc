# Deployment Checklist for influcalc

Follow these steps to deploy the Influencer CPA Calculator to GitHub Pages.

## ✅ Step-by-Step

### 1. Upload Files to GitHub

Go to: https://github.com/mot-displate/influcalc

Click **"Add file" → "Upload files"**

Drag and drop these files:
- ✅ `index.html`
- ✅ `.github/workflows/deploy.yml` (the entire `.github` folder)
- ✅ `README.md`
- ✅ `.gitignore`

Click **"Commit changes"**

---

### 2. Enable GitHub Pages

Go to: https://github.com/mot-displate/influcalc/settings/pages

Under **"Build and deployment":**
- Source: Select **"GitHub Actions"** from dropdown
- Click **Save**

---

### 3. Enable Workflow Permissions

Go to: https://github.com/mot-displate/influcalc/settings/actions

Scroll to **"Workflow permissions"**
- Select **"Read and write permissions"**
- Check ✅ **"Allow GitHub Actions to create and approve pull requests"**
- Click **Save**

---

### 4. Verify Deployment

Go to: https://github.com/mot-displate/influcalc/actions

You should see a deployment running (~30 seconds)

Once complete, visit: **https://mot-displate.github.io/influcalc/**

---

## 🔧 Troubleshooting

**No Actions running?**
- Make sure you uploaded the `.github/workflows/deploy.yml` file
- Check that the file is in the correct path (not in a subfolder)

**Deployment failed?**
- Go to Actions tab, click the failed workflow to see the error
- Most common: Pages not enabled or permissions not set

**404 error?**
- Wait 1-2 minutes for GitHub's CDN to update
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Verify `index.html` is in the root directory

---

## 📝 Notes

- The calculator includes password protection (same as brainwall)
- All calculations happen client-side (no backend needed)
- Page is private-repo-safe with the password prompt

---

**Need help?** Check the Actions tab for error logs.
