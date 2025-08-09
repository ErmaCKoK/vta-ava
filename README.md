# Avatar World Streaming - Website

Official website for Avatar World Streaming, a macOS application for immersive virtual avatar streaming.

## 🌟 Features

- **Custom Avatars**: Create and customize your own unique virtual avatar
- **Seamless Streaming**: Stream to Twitch, YouTube, and other platforms with zero latency
- **Motion Tracking**: Advanced motion tracking technology for natural avatar animation
- **Privacy First**: All processing happens locally on your Mac
- **Optimized Performance**: Built specifically for macOS with Metal optimization

## 🚀 Live Website

Visit our live website: [https://ermackok.github.io/vta-ava](https://ermackok.github.io/vta-ava)

## 📁 Project Structure

```
vta-ava/
├── index.html             # Main entry point (redirects to homepage)
├── homepage.html          # Main landing page
├── privacy-policy.html    # Privacy policy page
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions deployment workflow
└── README.md              # This file
```

## 🛠️ Development

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/ermackok/vta-ava.git
   cd vta-ava
   ```

2. Open `index.html` or `homepage.html` in your browser to view the website locally.

### Making Changes

1. Edit the HTML files as needed
2. Test locally by opening the files in your browser
3. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Update website content"
   git push origin main
   ```

## 🌐 GitHub Pages Setup

This website is automatically deployed to GitHub Pages using GitHub Actions.

### Automatic Deployment

- The website automatically deploys when you push to the `main` branch
- GitHub Actions workflow uses the official GitHub Pages deployment action
- Your website will be available at: `https://ermackok.github.io/vta-ava`

### Setup Instructions

1. **Enable GitHub Pages** in your repository settings:
   - Go to Settings → Pages
   - Under "Source", select "GitHub Actions"

2. **Grant Permissions** (if needed):
   - Go to Settings → Actions → General
   - Under "Workflow permissions", select "Read and write permissions"
   - Check "Allow GitHub Actions to create and approve pull requests"

### Troubleshooting

If you encounter deployment errors:

1. **Check Permissions**: Ensure the repository has proper GitHub Pages permissions
2. **Verify Settings**: Make sure GitHub Pages is enabled in repository settings
3. **Check Actions Logs**: Review the GitHub Actions logs for specific error messages
4. **Manual Deployment**: You can also manually deploy by:
   - Going to Settings → Pages
   - Selecting "Deploy from a branch"
   - Choosing "main" branch and "/ (root)" folder

## 📱 Pages

- **Homepage** (`homepage.html`): Main landing page with features, pricing, and download options
- **Privacy Policy** (`privacy-policy.html`): Comprehensive privacy policy for the app

## 🎨 Design Features

- Modern, responsive design
- Apple-inspired typography and styling
- Smooth animations and hover effects
- Mobile-optimized layout
- Professional color scheme with purple/blue gradients

## 🔧 Customization

### Colors
The website uses a purple/blue gradient theme:
- Primary: `#667eea`
- Secondary: `#764ba2`
- Accent: `#ff6b6b`

### Fonts
- System fonts: `-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif`

## 📄 License

© 2024 Avatar World Streaming. All rights reserved.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 📞 Support

For support or questions about the website:
- Email: support@avatarworldstreaming.com
- GitHub Issues: [Create an issue](https://github.com/ermackok/vta-ava/issues)

---
