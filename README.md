# Tower Day School Website

A modern, responsive website for Tower Day School - a Department of Early Education and Care licensed preschool in Lynnfield, Massachusetts, owned by Centre Congregational Church.

## About Tower Day School

Tower Day School offers preschool programs for children 2 years 9 months through 4 years old, and a transition to "K" class for those 4½ to 5 years. The school operates on a school year calendar between the hours of 8:30 AM and 3:00 PM.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Modern UI**: Clean, professional design with a cohesive color scheme
- **Multiple Pages**: Comprehensive information across dedicated pages
  - Home page with overview
  - About Us page with educational philosophy
  - Kindergarten program details
  - Admissions information and application process
  - Photo gallery with modal image viewer
  - School calendar and schedule
  - Contact information
- **Accessible Contact**: Clickable phone numbers using `tel:` links
- **Document Downloads**: PDF resources for applications, handbooks, and schedules
- **Social Media Integration**: Links to Facebook and YouTube

## Project Structure

```
New Tower/
├── index.html              # Home page
├── AboutUs.html            # About Us page
├── Admissions.html         # Admissions information
├── Contact.html            # Contact page
├── Gallery.html            # Photo gallery
├── Kindergarten.html       # Kindergarten program details
├── TDSCalendar.html        # School calendar
├── css/
│   └── styles.css         # Main stylesheet
├── images/                 # Image assets
│   ├── TDS_LOGO2017.jpg
│   └── [various photos]
└── assets/
    └── documents/          # PDF documents
        ├── TDSApplication.pdf
        ├── TDSApplicationInfo.pdf
        ├── TDS_HANDBOOK_2021.pdf
        ├── TDS_Calendar.pdf
        ├── TuitionSchedule.pdf
        └── Opening_Schedule.pdf
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables, flexbox, and grid
- **JavaScript**: Gallery modal functionality (minimal, vanilla JS)

## Setup & Usage

This is a static website that can be served using any web server. No build process or dependencies required.

### Deployment

The website is designed to be hosted on a Ubuntu VPS using Nginx. Deployment follows standard Nginx static site configuration:

1. Upload all files to the web server directory (typically `/var/www/html` or a site-specific directory)
2. Ensure Nginx is configured to serve the static files
3. Maintain the directory structure as shown in the Project Structure section
4. Set appropriate file permissions for the web server user

The site is deployed as a standard static HTML site with no build process required.

## Browser Support

The website is compatible with all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

**All Rights Reserved**

This website and its contents are owned by Centre Congregational Church for Tower Day School. 

**No part of this website may be used, copied, modified, or distributed without explicit written permission from:**
- The website maintainer/developer, or
- Centre Congregational Church

Unauthorized use is strictly prohibited.

---

**Last Updated**: January 2026
