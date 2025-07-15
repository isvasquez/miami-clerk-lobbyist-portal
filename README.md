# City of Miami Clerk's Office - Lobbyist Information Portal

A modern, responsive web application providing access to the City of Miami Clerk's Office lobbyist registrations and public records. Built with HTML, Tailwind CSS, and Alpine.js for a seamless user experience.

## Features

* **Responsive Design**: Optimized for desktop, tablet, and mobile devices
* **Dark Mode Toggle**: User-friendly dark/light theme switching with persistent preferences
* **Tabbed Navigation**: Organized content sections for easy browsing
* **PDF Document Access**: Direct links to lobbyist registration reports and documents
* **Modern UI/UX**: Clean, professional interface using Tailwind CSS
* **Accessibility**: TTY support and ADA-compliant design

## Available Content

### Active Registrations & Issues

* Annual lobbyist registration reports from 2015-2025
* Direct PDF access to all registration documents maintained by the Clerk's Office
* Database maintenance notice with alternative access methods

### Additional Resources

* Links to official City of Miami Clerk's Office lobbyist information
* External resources and guidelines for lobbyist compliance

### Contact Information

* **Phone**: (305)-250-5360
* **TTY**: 711 (Florida Relay Service)
* **Fax**: (305) 858-1610
* **Email**: clerks@miamigov.com
* **Website**: Office of the City Clerk
* **Location**: 3500 Pan American Drive, Miami, FL 33133

## Technology Stack

* **HTML5**: Semantic markup structure
* **Tailwind CSS**: Utility-first CSS framework for styling
* **Alpine.js**: Lightweight JavaScript framework for interactivity
* **Google Fonts**: Inter and Merriweather for typography

## Getting Started

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/yourusername/miami-clerk-lobbyist-portal.git
   cd miami-clerk-lobbyist-portal
   ```

2. **Open the application**:  
   * Simply open `index.html` in your web browser
   * No build process or server setup required

3. **Development**:  
   * Edit `index.html` to modify content or styling
   * The application uses CDN links for all dependencies

## Browser Support

* Chrome
* Firefox
* Safari
* Edge
* Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Adding New Content

1. Locate the appropriate tab section in `index.html`
2. Add new list items following the existing pattern:
   ```html
   <li><a href="path/to/document.pdf" target="_blank" class="list-item-link">
       <strong>Document Title</strong>
       <span class="text-blue-600 font-semibold">View PDF</span>
   </a></li>
   ```

### Styling Modifications

* Modify the `<style>` section in the HTML file
* Update Tailwind classes for layout changes
* Customize dark mode colors in the CSS variables

## Project Structure

```
miami-clerk-lobbyist-portal/
├── index.html          # Main application file
├── README.md           # Project documentation
├── .gitignore          # Git ignore rules
└── app/                # Application directory (if needed)
```

## Contributing

For questions or suggestions regarding the City of Miami Clerk's Office lobbyist information, please contact the Clerk's Office directly or visit the official City of Miami website.

## License

This project is maintained by the City of Miami Clerk's Office. All rights reserved.

## Contact

* **Website**: www.miamigov.com
* **Email**: clerks@miamigov.com
* **Phone**: (305)-250-5360
* **TTY**: 711 (Florida Relay Service)

---

_Last updated: January 2025_ 