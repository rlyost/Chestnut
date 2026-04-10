# Chestnut Auto & Towing - Website

Website for Chestnut Auto & Towing, a family-owned auto repair and towing shop at 160 Chestnut St Unit B, Redwood City, CA 94063. In business since 1989.

Phone: (650) 249-0444
Website: https://www.autorepairsredwoodcity.com/


## Files

- **index.html** - The complete website bundled as a single self-contained HTML file. All CSS, JavaScript, and images are inlined. Drop this on any web server and it works.
- **logo.svg** - Business logo (SVG with embedded raster image)
- **car-hero-img-796w.webp** - Hero section photo (car on lift)
- **welcome-img-627w.webp** - About section photo (technician working in shop)
- **Marketing-Audit-Chestnut-Automotive.pdf** - Marketing audit report (April 2026)


## What the Site Includes

**Sections:** Header with sticky nav, hero with CTAs, trust bar, 16 services with "Show All Services" toggle, service area banner, about/story, photo gallery, warranty banner, customer reviews, contact form with map, footer with areas served.

**Bilingual:** Full English/Spanish toggle in the navigation. All content translates when toggled.

**Local SEO:**
- JSON-LD structured data (AutoRepair schema) with 10 cities in areaServed
- Open Graph and Twitter Card meta tags
- Geo meta tags (latitude/longitude)
- Meta description targeting Redwood City, Palo Alto, San Mateo
- City names woven naturally into copy throughout the site
- Footer "Areas We Serve" section listing all target communities

**Services (16 total):** Oil Change, Brake Service, Engine Repair & Diagnostics, Transmission Repair, A/C Repair, Tire Services, Towing, Electrical Systems, Suspension Repair, 4x4 Service, Diesel Repair, Vehicle Inspection, Heating & Cooling, Steering Service, Exhaust & Muffler, DMV Vehicle Registration. First 8 visible by default with "Show All Services" button to reveal the rest.

**Mobile:** Sticky bottom CTA bar with Call and Book buttons appears on scroll. Responsive layout throughout.


## Google Analytics Setup

The site has Google Analytics 4 (GA4) code pre-installed. To activate it:

1. Go to https://analytics.google.com
2. Create a property for autorepairsredwoodcity.com
3. Get your Measurement ID (looks like G-XXXXXXXXXX)
4. Open index.html in a text editor
5. Find and replace both instances of `G-XXXXXXXXXX` with your real Measurement ID
6. Re-upload the file to your server

The GA script loads asynchronously so it won't slow down the page.


## How to Update Content

The site is a single HTML file. To make text changes, open index.html in any text editor and search for the text you want to change. Common updates:

- **Phone number:** Search for `249-0444`
- **Address:** Search for `160 Chestnut`
- **Hours:** Search for `8:00 AM - 6:00 PM`
- **Reviews count:** Search for `255+`

For adding real gallery photos, the placeholder images can be replaced by swapping in base64-encoded image data or by converting the site to a multi-file setup with an images folder.


## Tech Stack

Built with React 18, TypeScript, Tailwind CSS, and shadcn/ui components. Bundled to a single file using Parcel and html-inline. No server-side dependencies. No external JavaScript dependencies at runtime (everything is inlined).


## Hosting

This is a static site. It can be hosted anywhere: Netlify, Vercel, GitHub Pages, any shared hosting, S3, or directly on the current Kukui platform by replacing the existing site files. Upload index.html as the root file and you're live.
