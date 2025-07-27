# BASSL - Bay Area Shia Sports League Website

A modern, responsive website for the Bay Area Shia Sports League, built with HTML5, CSS3, and minimal JavaScript for easy maintenance and editing.

## 🌟 Features

- **Fully Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Easy to Edit**: Built with HTML5 and CSS3 - no complex frameworks
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Accessibility**: WCAG compliant with keyboard navigation support
- **Fast Loading**: Optimized CSS and minimal JavaScript for quick load times

## 📁 Project Structure

```
BASSL/
├── index.html          # Home page
├── teams.html          # Teams listing page
├── schedule.html       # Games schedule page
├── standings.html      # League standings page
├── contact.html        # Contact and registration page
├── css/
│   └── style.css      # Main stylesheet
├── images/            # Image assets (add your images here)
├── js/                # JavaScript files (minimal usage)
└── README.md          # This file
```

## 🎨 Design Features

### Color Scheme (Based on BASSL Logo)
- **Primary Dark Green**: `#1a3d2e` - Headers, navigation, primary elements
- **Primary Green**: `#2d5a3d` - Gradients, secondary elements
- **Accent Emerald**: `#4a9b5e` - Buttons, links, highlights
- **Accent Light**: `#6bb77b` - Light accents, hover states
- **Cream Background**: `#f5f3f0` - Page background matching logo
- **Text Dark**: `#2c3e2d` - Primary text color

### Typography
- **Font Family**: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Responsive Font Sizes**: Scales appropriately on all devices
- **Clear Hierarchy**: Proper heading structure (H1-H6)

### Layout
- **CSS Grid & Flexbox**: Modern layout techniques
- **Mobile-First**: Designed for mobile, enhanced for desktop
- **Container Max-Width**: 1200px for optimal reading experience

## 📱 Pages Overview

### 1. Home Page (`index.html`)
- Hero section with league introduction
- About BASSL section with key features
- Upcoming games preview
- Latest news and updates
- Call-to-action sections

### 2. Teams Page (`teams.html`)
- Soccer teams with detailed information
- Basketball teams (launching September 2024)
- Team registration information
- Individual team cards with logos and details

### 3. Schedule Page (`schedule.html`)
- Filterable game schedule (All, Upcoming, Completed, by Sport)
- Upcoming games table
- Recent results with scores
- Venue information
- Interactive filtering with minimal JavaScript

### 4. Standings Page (`standings.html`)
- Current soccer league table
- Team statistics and form
- Individual player statistics
- Basketball standings placeholder
- Key upcoming matches

### 5. Contact Page (`contact.html`)
- Contact information and office hours
- Registration forms for players and teams
- Venue details and locations
- FAQ section
- Volunteer opportunities

## 🛠️ How to Edit Content

### Updating Team Information
1. Open `teams.html`
2. Find the team card you want to edit
3. Update the team name, captain, venue, or description
4. Save the file

### Adding New Games to Schedule
1. Open `schedule.html`
2. Find the appropriate table (upcoming or completed)
3. Add a new `<tr>` row with game details
4. Include the appropriate classes (`upcoming`, `completed`, `soccer`, `basketball`)

### Updating Standings
1. Open `standings.html`
2. Find the standings table
3. Update team positions, statistics, and points
4. Update the form indicators (W/D/L)

### Changing Colors
1. Open `css/style.css`
2. Find the CSS custom properties at the top
3. Update color values as needed
4. The changes will apply site-wide

### Adding Images
1. Add your images to the `images/` folder
2. Update the `src` attributes in HTML files
3. Recommended image formats: JPG, PNG, WebP
4. Optimize images for web (compress for faster loading)

## 📋 Content Management Tips

### Adding News/Updates
- Edit the news section on `index.html`
- Keep descriptions concise (2-3 sentences)
- Include dates for all news items
- Link to contact page for registration

### Updating Contact Information
- Edit contact details in `contact.html`
- Update footer information across all pages
- Ensure email addresses and phone numbers are current

### Managing Venues
- Update venue information in both `schedule.html` and `contact.html`
- Include complete addresses and contact information
- Add capacity and facility details

## 🚀 Deployment

This website can be deployed to any web hosting service:

1. **GitHub Pages**: Push to GitHub and enable Pages
2. **Netlify**: Drag and drop the folder to Netlify
3. **Vercel**: Connect your GitHub repository
4. **Traditional Hosting**: Upload files via FTP

## 📱 Mobile Responsiveness

The website is fully responsive with breakpoints at:
- **Mobile**: 480px and below
- **Tablet**: 768px and below
- **Desktop**: 1200px and above

### Mobile Features
- Collapsible navigation menu
- Touch-friendly buttons and links
- Optimized table scrolling
- Readable font sizes on all devices

## ⚡ Performance Optimization

- **Minimal JavaScript**: Only essential functionality
- **Optimized CSS**: Efficient selectors and minimal redundancy
- **Image Optimization**: Compress images before adding
- **Clean HTML**: Semantic structure for better performance

## 🔧 Browser Support

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile Browsers**: iOS Safari, Chrome Mobile, Samsung Internet
- **Graceful Degradation**: Works on older browsers with reduced features

## 📞 Support

For technical questions about editing the website:
- Review this README file
- Check the comments in the CSS file
- Test changes on a local copy first
- Keep backups of working versions

## 🎯 Future Enhancements

Potential additions that maintain the simple structure:
- Photo gallery page
- Player statistics page
- Sponsor/partner page
- Event calendar integration
- Simple blog/news section

## 📄 License

This website template is created for the Bay Area Shia Sports League (BASSL). Feel free to modify and customize as needed for your organization.

---

**Built with ❤️ for the BASSL community**

*Last updated: July 2024*
