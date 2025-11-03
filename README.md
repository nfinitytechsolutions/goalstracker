# Goals Tracker Landing Page

A sleek, elegant, and modern landing page for the Goals Tracker mobile app.

## Features

- **Responsive Design**: Works beautifully on all devices (desktop, tablet, mobile)
- **Modern Gradient Background**: Eye-catching purple gradient hero section
- **Download Buttons**: Ready for iOS and Android app links (currently showing "Coming Soon")
- **Features Grid**: Showcases 6 key features with icons and descriptions
- **Stats Section**: Highlights unlimited capabilities
- **Footer**: Complete with quick links, support, and social media links
- **Smooth Animations**: Fade-in effects and hover animations
- **SEO Optimized**: Proper meta tags and semantic HTML

## Customization

### Update Download Links

Replace the `#` in the download buttons with your actual app store links:

```html
<!-- For iOS -->
<a href="https://apps.apple.com/your-app-link" class="btn-download">

<!-- For Android -->
<a href="https://play.google.com/store/apps/details?id=com.nfit" class="btn-download">
```

Remove the `coming-soon` class when apps are available.

### Change Colors

Edit the CSS variables in the `:root` section:

```css
:root {
    --primary: #6366F1;        /* Main brand color */
    --primary-dark: #4F46E5;   /* Darker shade */
    --primary-light: #818CF8;  /* Lighter shade */
}
```

### Update Social Links

Replace the `#` in social media links with your actual profiles:

```html
<a href="https://facebook.com/yourpage" class="social-link">
<a href="https://twitter.com/yourhandle" class="social-link">
<a href="https://instagram.com/yourhandle" class="social-link">
```

### Add Screenshots

To add app screenshots, insert this code after the features section:

```html
<section class="screenshots">
    <div class="container">
        <h2 class="section-title">See It In Action</h2>
        <div class="screenshot-gallery">
            <img src="screenshot1.png" alt="Goals Tracker Screenshot 1">
            <img src="screenshot2.png" alt="Goals Tracker Screenshot 2">
            <img src="screenshot3.png" alt="Goals Tracker Screenshot 3">
        </div>
    </div>
</section>
```

## Deployment

### Option 1: GitHub Pages

1. Create a repository on GitHub
2. Push the index.html file
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify

1. Sign up at netlify.com
2. Drag and drop the folder
3. Get instant deployment with custom domain support

### Option 3: Vercel

1. Sign up at vercel.com
2. Import your project
3. Deploy with one click

### Option 4: Custom Domain

Upload the index.html file to your web hosting service at:
- `https://goalstracker.app/index.html`

## File Structure

```
goalstracker/
├── index.html          # Main landing page
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Fast loading (single HTML file)
- No external dependencies
- Optimized animations
- Minimal JavaScript

## Contact

For questions or support, email: info@nfinityinfotech.com

## License

© 2025 Goals Tracker by NFinity Infotech. All rights reserved.
