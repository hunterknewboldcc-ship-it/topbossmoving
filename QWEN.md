# Top Boss Moving Website - Project Overview

## Project Description
Top Boss Moving LLC is a family-owned professional moving service headquartered in St. George, Utah. The website serves as an online presence for this moving company, showcasing their services, reputation, and contact information. The company specializes in local residential moves across Southern Utah, including the Kanab area, and has nearly a decade of experience with an impressive track record of 125+ five-star reviews.

## Website Architecture
The website consists of 6 main HTML pages:
- `index.html` - Main landing page with hero section and services preview
- `about.html` - Company history and credentials
- `services.html` - Detailed service offerings and pricing
- `contact.html` - Contact form and phone number for quotes
- `faq.html` - Frequently asked questions organized by category
- `reviews.html` - Customer testimonials and ratings

## Technology Stack
- **CSS Framework**: Tailwind CSS (loaded via CDN)
- **Icon Library**: Lucide Icons (loaded via CDN)
- **Font**: Google Fonts Inter family
- **Architecture**: Static HTML/CSS/JS (no backend required)
- **Contact Form**: Serverless function using Netlify Forms
- **Deployment**: GitHub Pages via GitHub Actions workflow

## Design System
The website follows a consistent color palette:
- **Navy Blue**: `#0B2338` (primary brand color)
- **Gold**: `#C89A3A` (accent/highlight color)
- **Orange**: `#C86A26` (CTA buttons)
- **Cream**: `#F5F0E6` (background color)

Typography uses the Inter font family with a clean, professional hierarchy.

## Key Features
- Responsive design with mobile navigation
- Interactive elements using JavaScript (mobile menu toggle)
- Consistent navigation across all pages
- SEO-friendly meta tags and descriptions
- Trust indicators (license number, years in business, review count)
- Service area information
- Contact information prominently displayed

## Deployment
The website is automatically deployed to GitHub Pages when changes are pushed to the main branch. The workflow is defined in `.github/workflows/static.yml`.

## Business Information
- **Established**: 2018
- **License**: MSB24-000431
- **Location**: St. George, UT (serving Southern Utah, Las Vegas, Phoenix)
- **Phone**: (435) 862-0699
- **Email**: topbossmoving@gmail.com
- **Pricing**: $105-$150/hour for loading/unloading services
- **Crew**: 2-mover teams

## Development Notes
- All pages share consistent header, footer, and styling
- Placeholder images are used throughout (marked with comments to replace with real images)
- Mobile-first responsive design approach
- Accessibility considerations with semantic HTML and proper contrast ratios
- Fast loading times due to minimal external dependencies

## File Structure
```
topbossmoving/
├── index.html          # Homepage
├── about.html          # Company information
├── services.html       # Service offerings
├── contact.html        # Contact form and info
├── faq.html            # Frequently asked questions
├── reviews.html        # Customer testimonials
├── README.md           # Basic project info
├── Read me.md          # Company description
├── LICENSE             # MIT License
└── .github/workflows/static.yml  # GitHub Actions deployment
```

## Maintenance Requirements
- Replace placeholder images with actual photos of the moving team and services
- Regular updates to customer reviews
- Monitor and update contact information
- Periodic review of service areas and pricing