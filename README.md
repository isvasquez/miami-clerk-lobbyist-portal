# City of Miami Clerk's Office - Lobbyist Information Portal

A modern, responsive web application providing access to the City of Miami Clerk's Office lobbyist registrations and public records. Built with HTML, Tailwind CSS, and Alpine.js for a seamless user experience.

---

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Dark Mode Toggle**: User-friendly dark/light theme switching with persistent preferences
- **Tabbed Navigation**: Organized content sections for easy browsing
- **PDF Document Access**: Direct links to lobbyist registration reports and documents
- **Modern UI/UX**: Clean, professional interface using Tailwind CSS
- **Accessibility**: TTY support and ADA-compliant design

---

## Available Content

### Active Registrations & Issues
- Annual lobbyist registration reports from 2015-2025
- Direct PDF access to all registration documents maintained by the Clerk's Office
- Database maintenance notice with alternative access methods

### Additional Resources
- Links to official City of Miami Clerk's Office lobbyist information
- External resources and guidelines for lobbyist compliance

### Contact Information
- **Phone**: (305)-250-5360
- **TTY**: 711 (Florida Relay Service)
- **Fax**: (305) 858-1610
- **Email**: clerks@miamigov.com
- **Website**: Office of the City Clerk
- **Location**: 3500 Pan American Drive, Miami, FL 33133

---

## Technology Stack

- **HTML5**: Semantic markup structure
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Alpine.js**: Lightweight JavaScript framework for interactivity
- **Google Fonts**: Inter and Merriweather for typography

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/edgarvelr/miami-clerk-lobbyist-portal.git
   cd miami-clerk-lobbyist-portal
   ```
2. **Open the application:**
   - Simply open `index.html` in your web browser
   - No build process or server setup required
3. **Development:**
   - Edit `index.html` to modify content or styling
   - The application uses CDN links for all dependencies

---

## Content Management Guide

### Adding New Tabs
1. **Add Tab Button**
   - Locate the tab navigation section in `index.html` and add a new button:
     ```html
     <button @click="activeTab = 'new-tab-id'" ...>New Tab Name</button>
     ```
2. **Add Tab Content**
   - Add the corresponding content section after the existing tabs:
     ```html
     <div x-show="activeTab === 'new-tab-id'" ...>
       <h2>New Tab Name</h2>
       <ul>...</ul>
     </div>
     ```

### Removing Tabs
- Remove the button and the corresponding content section.
- Update the default tab if needed.

### Adding Content to Existing Tabs
- For simple lists:
  ```html
  <li><a href="path/to/document.pdf" target="_blank" class="list-item-link">
      <strong>Document Title</strong>
      <span class="text-blue-600 font-semibold">View PDF</span>
  </a></li>
  ```
- For accordion sections (see Monthly Reports in the HTML for an example):
  - Add a new accordion `<div x-data="{ open: false }">...</div>`

### Removing Content
- Delete the corresponding `<li>` or accordion `<div>` section.

### Best Practices
- Use consistent naming: "Document Type - Year"
- Group related documents together
- Maintain chronological order (newest first)
- Test all links after adding

---

## Customization & Styling

- Modify the `<style>` section in the HTML file for custom styles
- Update Tailwind classes for layout changes
- Customize dark mode colors in the CSS variables
- Use Tailwind's responsive prefixes (`sm:`, `md:`, `lg:`, `xl:`) for layout

---

## Troubleshooting

- **Tab Not Showing:** Ensure the `activeTab` value matches between the button and content section
- **Accordion Not Working:** Check that Alpine.js is loaded and `x-data="{ open: false }"` is present
- **Styling Issues:** Verify Tailwind CSS is loading properly
- **Links Not Working:** Test URLs in browser and ensure they're accessible
- **Dark Mode:** Make sure the toggle works and localStorage is enabled

---

## Project Structure

```
miami-clerk-lobbyist-portal/
├── index.html          # Main application file
├── README.md           # Project documentation
├── .gitignore          # Git ignore rules
└── app/                # Application directory (if needed)
```

---

## License

This project is maintained by the City of Miami Clerk's Office. All rights reserved.

## Contact

- **Website**: www.miamigov.com
- **Email**: clerks@miamigov.com
- **Phone**: (305)-250-5360
- **TTY**: 711 (Florida Relay Service)

---

_Last updated: January 2025_ 