# Puerto Varas Real Estate - GitHub Pages Website

A professional Jekyll-based website for Puerto Varas Real Estate, showcasing property flips and rental management services.

## Features

- 🏠 **Property Flips** - Information about our property flipping services
- 🏡 **Long-Term Rentals** - Long-term rental property management
- 🌴 **Short-Term Rentals** - Vacation rental management services
- 📱 **Responsive Design** - Works beautifully on all devices
- ⚡ **Fast & Modern** - Built with Jekyll for fast loading times

## Setup Instructions

### Prerequisites

- Ruby (version 2.5 or higher)
- Bundler gem

### Local Development

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run Jekyll locally:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View the site:**
   Open your browser and navigate to `http://localhost:4000`

### GitHub Pages Deployment

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository settings on GitHub
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select the branch (usually `main` or `master`)
   - Select the folder (usually `/ (root)`)
   - Click "Save"

3. **Wait for deployment:**
   GitHub Pages will automatically build and deploy your site. It may take a few minutes.

## Customization

### Update Contact Information

Edit `_config.yml` to update:
- Email address
- Social media links
- Site description

### Update Contact Form

The contact form uses Formspree. To enable it:
1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form
3. Replace `YOUR_FORM_ID` in `index.html` with your Formspree form ID

### Modify Content

- **Homepage:** Edit `index.html`
- **Styling:** Edit `assets/css/style.css`
- **Layout:** Edit `_layouts/default.html`

## File Structure

```
.
├── _config.yml          # Jekyll configuration
├── _layouts/
│   └── default.html     # Base layout template
├── assets/
│   └── css/
│       └── style.css    # Main stylesheet
├── index.html           # Homepage
├── Gemfile              # Ruby dependencies
├── .gitignore           # Git ignore rules
└── README.md            # This file
```

## License

All rights reserved © Puerto Varas Real Estate

