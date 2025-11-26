# Giriraj Government College Website

## Overview
A comprehensive multipage website for Giriraj Government College (Autonomous), Nizamabad, Telangana.

## Features
- ✅ Multipage website structure with 20 pages
- ✅ Auto-scrolling hero image slider on homepage (9 real college photos, changes every 5 seconds)
- ✅ Real college images integrated throughout (images folder included)
- ✅ Professional gallery page with actual event photos
- ✅ Responsive design for all devices
- ✅ Consistent navigation across all pages
- ✅ Modern, professional design with gradients and smooth transitions
- ✅ Dropdown menus for College section
- ✅ Contact form with validation
- ✅ Interactive gallery with hover effects
- ✅ Comprehensive course tables
- ✅ Department information
- ✅ Footer with important links on every page

## Website Structure

### Main Pages
1. **index.html** - Home page with hero slider (9 auto-scrolling real college images)
2. **about.html** - About the college, history, values
3. **vision-mission.html** - Vision, mission, and strategic goals
4. **courses.html** - Detailed course offerings with tables
5. **departments.html** - Academic departments information
6. **administration.html** - College administration and offices
7. **examination.html** - Examination branch details
8. **support-services.html** - Library, labs, health center info
9. **achievements.html** - College achievements and accolades
10. **gallery.html** - Campus gallery with image placeholders
11. **activities.html** - Student activities and clubs
12. **news-events.html** - Latest news and upcoming events
13. **team.html** - Faculty and staff information
14. **contact.html** - Contact form and college details
15. **career-placements.html** - Career services and placements
16. **rti.html** - Right to Information details
17. **downloads.html** - Downloadable forms and documents
18. **login.html** - Student/Staff login portal
19. **nirf.html** - NIRF ranking data

### Assets
- **css/style.css** - Comprehensive stylesheet for all pages

## Key Design Elements

### Color Scheme
- Primary Blue: #1e3c72, #2a5298 (college colors)
- Accent Red: #e74c3c, #c0392b (NIRF badge, highlights)
- Green: #27ae60 (checkmarks, success)
- Gray: #f8f9fa, #e9ecef (backgrounds)
- Dark: #2c3e50, #34495e (navigation)

### Hero Slider
The homepage features an auto-scrolling hero section with 3 different slides:
1. Blue theme - Welcome message
2. Green theme - Excellence in Education
3. Red theme - Building Future Leaders

Slides change automatically every 5 seconds with smooth fade transitions.

### Navigation
- Sticky navigation bar that stays at top while scrolling
- Dropdown menu under "College" with 6 sub-pages
- Mobile-responsive hamburger menu for small screens
- Active page highlighting

### Top Bar
Quick access links to:
- Career & Placements
- R.T.I (Right to Information)
- Contact
- Downloads
- Login To College

## College Information

**Name:** Giriraj Government College (Autonomous)
**Location:** Dubba Road, Nizamabad, 503002, Telangana
**Phone:** 08462-222222
**Email:** sai@documounttech.in
**Affiliation:** Telangana University
**Accreditation:** NAAC 'B' Grade

## Technical Details

### Browser Compatibility
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

### Responsive Breakpoints
- Desktop: 1200px and above
- Tablet: 768px to 1199px
- Mobile: below 768px

### JavaScript Features
- Mobile menu toggle
- Hero slider auto-scroll
- Form validation
- Smooth scrolling navigation
- Active page highlighting

## Customization Guide

### To Add Your Images:
Replace the gradient placeholders in gallery.html and hero slider with actual images:
```html
<!-- Replace this -->
<div class="gallery-placeholder">🏛️</div>

<!-- With actual image -->
<img src="path/to/image.jpg" alt="Description">
```

### To Update Hero Slider Images:
Edit the background styles in css/style.css:
```css
.hero-slide-1 {
    background: url('path/to/image1.jpg');
    background-size: cover;
}
```

### To Change Colors:
Search and replace color codes in css/style.css

### To Add New Pages:
1. Copy any existing HTML file
2. Update the page title and content
3. Add link to navigation menu
4. Update footer links if needed

## Deployment

### Steps to Deploy:
1. Upload all files maintaining the folder structure
2. Ensure css folder is in the same directory as HTML files
3. Test all links and navigation
4. Verify responsiveness on different devices
5. Add actual content, images, and data

### Required Files:
```
/
├── index.html
├── about.html
├── [other html files...]
└── css/
    └── style.css
```

## Future Enhancements
- Add actual photographs for gallery
- Implement backend for contact form
- Add online admission system
- Student/faculty login functionality
- Result publication system
- Notice board with dynamic updates
- Alumni portal
- Online library access
- Video gallery
- Virtual campus tour

## Credits
**Developed by:** SAILU MILTRY
**Year:** 2025
**Institution:** Giriraj Government College

## Support
For any questions or customizations:
- Email: sai@documounttech.in
- Phone: 08462-222222
