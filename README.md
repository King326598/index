# QR Code Generator - Redirect Repository

This repository provides an instant redirect from your main GitHub Pages domain to your QR Code Generator application.

## 📁 Repository Structure

```
index/
├── index.html    # Instant redirect file
└── README.md     # This documentation
```

## 🚀 How It Works

This repository serves as a redirect hub that immediately forwards visitors from your main GitHub Pages domain to your QR Code Generator application.

### Redirect Mechanism:
1. **Instant JavaScript Redirect**: `window.location.replace()` - No loading screen
2. **Meta Refresh Fallback**: For browsers with JavaScript disabled
3. **Noscript Fallback**: Manual link for edge cases

## 🔧 Setup Instructions

### Step 1: Update Redirect URL
Edit `index.html` and replace `yourusername` with your actual GitHub username:

```html
window.location.replace("https://king326598.github.io/qr-code-generator/");
```

### Step 2: Deploy to GitHub Pages

1. **Create GitHub Repository**:
   - Go to [GitHub.com](https://github.com) → New repository
   - Name it (e.g., `index`, `redirect`, or your main project name)
   - Make it **Public**
   - Click "Create repository"

2. **Upload Files**:
   ```bash
   git add .
   git commit -m "Initial redirect setup"
   git push origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Select "main" branch as source
   - Your site will be at: `https://king326598.github.io/repository-name/`

### Step 3: Google AdSense Setup
- Use your main repository URL: `https://king326598.github.io/repository-name/`
- This redirect repository ensures Google can crawl your main domain
- Users get seamlessly redirected to your QR Code Generator

## 🎯 Use Cases

- **Main Domain Redirect**: Forward main GitHub Pages to your app
- **Google AdSense**: Satisfies domain requirements
- **Clean URLs**: Hide subdirectory structure from users
- **Multiple Projects**: Route different subdomains to different apps

## 🔄 Update Redirect Destination

To redirect to a different repository, update the URL in `index.html`:

```javascript
window.location.replace("https://king326598.github.io/different-repo/");
```

## 📝 Customization

You can customize the redirect behavior by modifying the `index.html` file:
- Change redirect delay (currently instant)
- Add loading messages (if desired)
- Modify fallback behavior

---

**Made with ❤️ for seamless GitHub Pages deployment**
