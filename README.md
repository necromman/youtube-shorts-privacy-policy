# Privacy Policy for YouTube Shorts Shortcuts & Autoplay

This repository hosts the privacy policy for the YouTube Shorts Shortcuts & Autoplay Chrome Extension.

## Setup Instructions

### 1. Create a New GitHub Repository

1. Go to [GitHub](https://github.com/new)
2. Create a new repository named: `youtube-shorts-privacy-policy` (or similar)
3. Set it as **Public** (required for GitHub Pages)
4. Don't initialize with README (we already have one)

### 2. Push This Privacy Policy

```bash
# Navigate to the privacy-policy folder
cd privacy-policy

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Add privacy policy for YouTube Shorts extension"

# Add your repository as origin (replace with your repo URL)
git remote add origin https://github.com/necromman/youtube-shorts-privacy-policy.git

# Push to main branch
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository settings
2. Scroll to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Select "main" branch and "/ (root)" folder
5. Click "Save"

### 4. Your Privacy Policy URL

After a few minutes, your privacy policy will be available at:
```
https://YOUR_USERNAME.github.io/youtube-shorts-privacy-policy/
```

### 5. Add to Chrome Web Store

1. Go to Chrome Web Store Developer Dashboard
2. Edit your extension listing
3. In the "Privacy" section, add your GitHub Pages URL
4. Save and resubmit for review

## Information to Update

Before publishing, update these placeholders in `index.html`:

- **[YOUR_EMAIL_HERE]**: Your contact email address
- **[YOUR_GITHUB_PROFILE_HERE]**: Your GitHub profile URL (e.g., https://github.com/yourusername)
- **[CHROME_WEBSTORE_SUPPORT_URL]**: Your extension's support URL (optional)

## Alternative Hosting Options

If you prefer not to use GitHub Pages, you can host this privacy policy on:

- **Netlify**: Drop the folder and get instant hosting
- **Vercel**: Deploy with one click
- **GitLab Pages**: Similar to GitHub Pages
- **Your own website**: If you have one

## License

This privacy policy template is provided as-is for the YouTube Shorts Shortcuts & Autoplay extension.