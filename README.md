# Bounce Board Pro - Landing Page

A minimalist, dark-themed landing page for Bounce Board Pro, built with Jekyll and Bootstrap 5.

## 🚀 Quick Start

### Local Development

1. **Install Jekyll** (if not already installed):
   ```bash
   gem install bundler jekyll
   ```

2. **Install dependencies**:
   ```bash
   bundle install
   ```

3. **Run the development server**:
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site**: Open [http://localhost:4000](http://localhost:4000) in your browser

### GitHub Pages Deployment

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial landing page"
   git push origin master
   ```

2. **Enable GitHub Pages**:
   - Go to your repository Settings > Pages
   - Select the `master` branch (or `main` if using that)
   - Select `/ (root)` as the source
   - Save

3. **Configure Jekyll** (if needed):
   - GitHub Pages will automatically build the site
   - The `CNAME` file is already configured for `bounceboardpro.com`

## 📧 MailerLite Integration

To integrate MailerLite:

1. **Create a form in MailerLite**:
   - Log in to your MailerLite account
   - Go to Forms > Create Form
   - Choose "Embedded Form"
   - Customize the form styling to match the dark theme

2. **Get the embed code**:
   - In your form settings, go to "Embed"
   - Copy the embed code

3. **Replace the form in `index.html`**:
   - Open `index.html`
   - Find the `<!-- MailerLite Embed Form -->` section
   - Replace the placeholder form with your MailerLite embed code

Alternatively, you can use the MailerLite API for a more custom integration.

## 🎨 Customization

### Colors

The color scheme is defined in `assets/css/main.css`:
- Accent Red: `#D93838`
- Background Black: `#000000`
- Background Dark: `#1a1a1a`

### Typography

- Headings: Poppins (bold)
- Body: Inter

Both fonts are loaded from Google Fonts in `_layouts/default.html`.

## 📁 Project Structure

```
.
├── _config.yml          # Jekyll configuration
├── _layouts/
│   └── default.html     # Main layout template
├── assets/
│   ├── css/
│   │   └── main.css     # Custom styles
│   └── js/
│       └── main.js      # Form validation
├── index.html           # Landing page
├── privacy.html         # Privacy policy page
├── CNAME                # Custom domain configuration
└── Gemfile              # Ruby dependencies
```

## ✅ Features

- ✅ Dark theme with premium aesthetic
- ✅ Fully responsive (mobile-first)
- ✅ Bootstrap 5 components
- ✅ Minimal custom CSS
- ✅ Smooth scrolling
- ✅ Form validation
- ✅ Privacy policy page
- ✅ Ready for MailerLite integration

## 🔮 Future Enhancements

The site is structured to easily add:
- Product gallery
- Video embeds
- FAQ section
- Pricing tiers
- Pre-order checkout
- Accessory modules
- Feature pages

## 📝 Notes

- The site intentionally keeps product details vague (per spec)
- No trademarked names or specific accessories are mentioned
- Placeholder images can be replaced with actual teaser visuals
- All sections are modular and easy to extend
