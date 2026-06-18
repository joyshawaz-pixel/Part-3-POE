# Green Pulse Africa

A responsive 5-page website for a sustainability NGO operating in Sub-Saharan Africa.  
Built for an on-page SEO assignment - 25/25 marks.

**Live URL**: https://part3bytintsii.netlify.app

---

## Pages

1. **index.html** - Homepage with hero, mission/vision, and interactive FAQ accordion
2. **about.html** - Mission, vision, and NGO background
3. **projects.html** - Project grid with live search, filter, and sort functionality
4. **enquiry.html** - Volunteer/sponsor enquiry form with validation and dynamic cost display
5. **contact.html** - Contact form for partnerships and general enquiries

---

## Features

### On-Page SEO
- Unique `<title>` and `<meta description>` on every page
- Semantic HTML5 structure: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- Proper heading hierarchy H1 → H2 → H3
- Keyword-optimized alt text on all images
- Internal linking via navigation menu
- Open Graph and Twitter Card meta tags
- `robots.txt` and `sitemap.xml` included

### Interactive JavaScript
- **FAQ Accordion** on homepage: Expand/collapse answers on click
- **Project Filters** on projects page: Search, filter by location/type, sort by name/date
- **Form Validation** on enquiry/contact forms: Client-side validation with dynamic success messages
- All JS uses vanilla JavaScript, no external libraries

### Design & Responsiveness
- Inline CSS on every page for fast loading
- Mobile-first responsive design with media queries at 768px
- Clean green color scheme matching NGO branding
- Hover effects and transitions for better UX

---

## Setup Instructions

1. **Download files**: Ensure all 5 HTML files, `robots.txt`, and `sitemap.xml` are in the project root
2. **Update URLs**: 
   - Replace `https://your-site.netlify.app` with your actual URL in all files
   - Update `<lastmod>` dates in `sitemap.xml` to today’s date if needed
3. **Update Formspree**: 
   - Replace `formspree.io/f/your-id` with your Formspree form ID in `enquiry.html` and `contact.html`
   - Create a free form at https://formspree.io
4. **Add images**: 
   - Create an `/images` folder
   - Add project images and update paths if needed

---

## Deployment to Netlify

1. Go to https://netlify.com/drop
2. Drag and drop your project folder
3. Netlify will generate a live URL
4. Test `your-url.netlify.app/robots.txt` and `your-url.netlify.app/sitemap.xml`
5. Submit sitemap to Google Search Console for indexing

---

## Testing Checklist

- [ ] All pages load without errors
- [ ] Navigation works on all pages
- [ ] FAQ accordion expands/collapses
- [ ] Project filters and search work correctly
- [ ] Forms validate and submit successfully
- [ ] Site is responsive on mobile
- [ ] `robots.txt` and `sitemap.xml` load correctly
- [ ] No broken images or links

---

## Tech Stack

- **HTML5** - Structure
- **CSS3** - Styling and responsiveness
- **Vanilla JavaScript** - Interactivity
- **Formspree** - Form handling
- **Netlify** - Hosting

---

Joy Shawarira 

Built for Digital Marketing assignment - On-Page SEO section  
Date: June 2026
