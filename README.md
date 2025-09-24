# Responsive Landing Page with Interactive Navigation

Take a look at Live Website : https://responsive-landing-page-u323.vercel.app/

This project is a responsive landing page featuring an interactive navigation menu that enhances user experience by dynamically changing its style when scrolling or hovering over menu items. The navigation menu remains fixed and visible across all sections/pages.

## Features

- **Fixed Navigation Bar**: Stays at the top of the page while scrolling.
- **Scroll Effect**: Navbar background changes color when scrolling past a certain point.
- **Hover Effect**: Menu items change color on hover.
- **Smooth Scrolling**: Clicking nav links smoothly scrolls to sections.
- **Responsive Design**: Adapts seamlessly across desktop, tablet, and mobile devices.
- **Mobile Menu**: Hamburger menu for mobile devices.
- **Reusable Components**: Navbar and footer are included as separate components for reusability.

## Project Structure

```
Responsive-Landing-Page/
│
├── index.html             # Main landing page
├── about.html             # About page
├── contact.html           # Contact page
│
├── /assets
│   ├── /css
│   │   ├── style.css      # Global styles
│   │   ├── responsive.css # Media queries for responsiveness
│   │
│   ├── /js
│   │   ├── script.js      # JavaScript for interactivity
│   │
│   ├── /images
│   │   ├── logo.png       # Logo image (placeholder)
│   │   ├── banner.jpg     # Hero banner image (placeholder)
│   │   └── ...            # Other assets
│
├── /components
│   ├── navbar.html        # Reusable navigation bar
│   └── footer.html        # Reusable footer
│
└── README.md              # Project documentation
```

## Setup Instructions

1. Clone or download the project files.
2. Open `index.html` in a web browser to view the landing page.
3. For development, use a local server to avoid CORS issues with component loading.

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- JavaScript (ES6+)

## Browser Support

- Chrome
- Firefox
- Safari
- Edge

## Customization

- **Colors**: Edit the CSS variables in `style.css`.
- **Content**: Update text and images in the HTML files.
- **Interactivity**: Modify the JavaScript in `script.js` for additional effects.

## License

This project is open source and available under the [MIT License](LICENSE).

