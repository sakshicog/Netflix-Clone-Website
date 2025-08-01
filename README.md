Netflix Clone Website (Front-end: HTML, CSS, JavaScript)

A visually rich, responsive landing page that mimics Netflix’s official homepage. It features a fixed header, a full-screen hero banner, horizontal carousels, feature cards, an FAQ accordion, and a footer. Built with semantic HTML, modern CSS (Flexbox, Grid, animations) and vanilla JavaScript for interactivity.

Problem Statement
Create a static front-end web page that recreates Netflix’s homepage layout and behavior. Users should be able to browse a “Trending Now” carousel, explore feature highlights, expand FAQs, switch languages, and see calls to action, all with smooth animations and responsive design.

Objective
Develop a fully responsive, stand-alone front-end clone of Netflix’s home page, demonstrating best practices in HTML structure, CSS layout and styling, and JavaScript-driven UI interactions.

Features Implemented
- Fixed Navbar with logo, language selector, and sign-out button aligned horizontally and always visible
- Hero Banner with full-viewport background image, centered heading, subtext, and CTA button with fade-in animation
- Horizontal Carousel for “Trending Now” posters, with left/right scroll buttons
- Feature Grid of four highlight cards (“Enjoy on your TV”, “Download & Go”, etc.) with hover lift effect
- FAQ Accordion with expandable panels and animated height transitions
- Footer with secondary CTA, help line, multi-column link list, and language selector

Technology Stack
Markup: Semantic HTML5
Styling: CSS3 (Flexbox, Grid, keyframe animations)
Scripting: Vanilla JavaScript (ES6)
Assets: Local images and SVG icons stored in an assets folder

Methodology
UI and Layout
Organized the page into logical sections (header, hero, carousel, features, FAQ, footer). Used a container utility to center and constrain content and applied Flexbox and Grid for alignment. Added smooth animations and hover effects to enhance user engagement.

Asset Management
Stored brand logo, hero background, carousel posters, and SVG icons under assets. Ensured images use correct aspect ratios and are optimized for web performance.

Interactivity and JavaScript
Implemented carousel scrolling via element.scrollBy() on arrow clicks. Built the FAQ accordion by toggling an active class on question buttons and animating max-height. Wired up language selectors and sign-out button with placeholder event handlers for future integration.

Responsive Design and Performance
Used CSS Grid with repeat(auto-fit, minmax()) to make feature cards adapt to different viewports. Enabled touch-friendly horizontal scrolling on carousels with overflow-x: auto and smooth scroll behavior. Minimized layout shifts by reserving image container sizes and using CSS transitions. Kept CSS and JavaScript payloads small by relying on native browser APIs and avoiding external frameworks.

To run
1. Place your images in the assets folder as outlined (logo.png, hero-bg.jpg, posters, icons).
2. Open index.html in a modern web browser.
