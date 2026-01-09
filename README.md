# Tesu Law - Professional Law Firm Website

A modern, responsive multi-page website for Tesu Law, a new-age law firm specializing in startup advisory, venture capital, intellectual property, and commercial litigation.

## Project Structure

```
tesu-law/
├── index.html              # Homepage with hero, services overview, and team preview
├── about.html              # About page with firm story, mission, vision, and values
├── services.html           # Practice areas with detailed service descriptions
├── team.html               # Team page with detailed attorney profiles
├── contact.html            # Contact page with form and office information
├── styles.css              # Main stylesheet with complete design system
├── README.md               # This file
└── assets/                 # All images and media files
    ├── tesulaw-logo-horizontal-black-vector.svg  # Firm logo
    ├── tesu-both.png       # Hero image of founding partners
    ├── raghav.jpg          # Team member photo
    ├── pranav.jpg          # Team member photo
    └── favicon.png         # Website favicon
```

## Technologies Used

- **HTML5**: Semantic markup for all pages
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **Vanilla JavaScript**: For interactive elements (popups, navigation, form handling)
- **Google Fonts**: Inter (sans-serif) and Playfair Display (serif)

## Design System

### Color Palette

- **Primary**: `#1a1a2e` (Dark navy)
- **Primary Dark**: `#0f0f1a` (Darker navy)
- **Accent**: `#c9a227` (Gold)
- **Text Primary**: `#1a1a2e`
- **Text Secondary**: `#4a4a5a`
- **Background**: `#ffffff` (White)
- **Light Gray**: `#f5f5f7`

### Typography

- **Headings**: Playfair Display (serif)
- **Body**: Inter (sans-serif)
- **Base Font Size**: 16px
- **Line Height**: 1.7

### Spacing

Uses CSS custom properties for consistent spacing:
- `--spacing-xs`: 0.5rem
- `--spacing-sm`: 1rem
- `--spacing-md`: 1.5rem
- `--spacing-lg`: 2rem
- `--spacing-xl`: 3rem
- `--spacing-2xl`: 4rem
- `--spacing-3xl`: 6rem

## Page Overview

### 1. Home (index.html)

**Purpose**: Main landing page showcasing the firm's value proposition

**Sections**:
- Hero with team image and CTAs
- Services overview grid (6 practice areas)
- Statistics section (experience, transactions, clients)
- Why choose us section
- Team preview
- CTA section

**Key Features**:
- Disclaimer popup on first visit (stored in localStorage)
- Responsive hero with team image
- Animated fade-in effects

### 2. About (about.html)

**Purpose**: Tell the firm's story and values

**Sections**:
- Firm story and background
- Mission and vision cards
- Core values (6 value cards)
- Why work with us
- Statistics

**Content Focus**: Establishing trust and credibility

### 3. Services (services.html)

**Purpose**: Detailed practice area descriptions

**Sections**:
- 6 detailed practice areas with representative work
- Industry focus section
- CTA

**Practice Areas**:
1. Startup & Founder Advisory
2. Venture Capital & Funding
3. Intellectual Property
4. Commercial Contracts
5. Dispute Resolution & Litigation
6. Regulatory Compliance

### 4. Team (team.html)

**Purpose**: Showcase attorney expertise

**Sections**:
- Detailed partner profiles with:
  - Professional background
  - Practice areas
  - Education & admissions
  - Notable matters
  - Direct contact links
- What sets our team apart

### 5. Contact (contact.html)

**Purpose**: Facilitate client outreach

**Sections**:
- Contact information with icons
- Contact form (mailto integration)
- FAQ section
- Direct partner contact info

## Responsive Breakpoints

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px max-width
- **Tablet**: 1024px and below
- **Mobile Landscape**: 900px and below
- **Mobile Portrait**: 768px and below
- **Small Mobile**: 480px and below

### Mobile Optimizations

- Hamburger navigation menu
- Stacked layouts for all grid sections
- Smaller typography and spacing
- Full-width buttons
- Simplified footer layout
- Optimized hero image sizing

## Key Features

### 1. Fixed Header

- Transparent on hero, solid white on scroll
- Smooth scroll behavior
- Mobile hamburger menu
- Active page highlighting

### 2. Disclaimer & Privacy Policy

- Initial disclaimer popup on homepage
- Stores acceptance in localStorage
- Both accessible from footer on all pages
- Modal popup implementation

### 3. Contact Form

- Client-side form validation
- Mailto integration for submissions
- Consent checkbox required
- Responsive layout

### 4. Hero Image

- Custom masking with gradients
- Responsive sizing across breakpoints
- Fade effect on bottom edge
- Optimized for mobile

### 5. Team Profiles

- Full detailed bios with credentials
- Professional photography
- Direct contact CTAs
- Hover effects on images

## Customization Guide

### Updating Colors

Edit CSS custom properties in `styles.css`:

```css
:root {
    --primary: #1a1a2e;
    --accent: #c9a227;
    /* ... other colors */
}
```

### Adding Team Members

1. Add new photo to project root
2. Duplicate a team profile section in `team.html`
3. Update image src, name, title, and bio
4. Add to homepage team preview in `index.html`

### Updating Contact Information

Update in all footer sections across pages:
- Email: `contact@tesulaw.com`
- Phone: `+91 99530 16904`

### Modifying Practice Areas

Edit service descriptions in `services.html`:
- Update section headings
- Modify practice lists
- Add/remove practice areas as needed

## Deployment

### Requirements

- Web server (Apache, Nginx, or static hosting)
- No server-side processing required
- HTTPS recommended for production

### Static Hosting Options

- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **GitHub Pages**: Free hosting for static sites
- **AWS S3 + CloudFront**: Scalable hosting

### Deployment Steps

1. Upload all files to web server
2. Ensure `index.html` is set as default document
3. Configure 404 redirects if needed
4. Set up SSL certificate
5. Update meta tags with production domain

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimizations

- Minified CSS for production (recommended)
- Optimized images (already compressed)
- Google Fonts with `preconnect`
- CSS Grid and Flexbox for layouts
- Minimal JavaScript usage

## Accessibility Features

- Semantic HTML5 elements
- ARIA labels on interactive elements
- Keyboard navigation support
- Focus states on all interactive elements
- Alt text on all images
- Sufficient color contrast ratios

## SEO Optimization

Each page includes:
- Unique meta titles
- Meta descriptions
- Open Graph tags for social sharing
- Twitter card support
- Semantic heading hierarchy

## Legal Compliance

- Disclaimer popup on first visit
- Privacy policy accessible from footer
- No cookies used (except localStorage for disclaimer)
- Contact form consent checkbox

## Maintenance

### Regular Updates

- Update team member information
- Add new case studies/representative work
- Update statistics annually
- Refresh testimonials if added
- Keep contact information current

### Content Updates

All content is in HTML files - no database required. Simply edit the HTML files and redeploy.

## Support & Contact

For technical issues or questions about this website:
- Email: contact@tesulaw.com
- Phone: +91 99530 16904

## License

Copyright © 2025 Tesu Law. All rights reserved.

---

**Built with**: Modern web standards, responsive design, and attention to user experience.
