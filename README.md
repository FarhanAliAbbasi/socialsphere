Social Sphere - Digital Agency Interactive Dashboard

Social Sphere is a premium, single-page interactive website template designed for digital marketing agencies. It combines high-end aesthetics (Dark Mode, Glassmorphism) with functional tools like a live cost calculator and data visualizations to engage potential clients.

Built with vanilla HTML, CSS (Tailwind), and JavaScript, it requires no build steps or complex backend, making it incredibly easy to deploy and customize.

📑 Table of Contents

Features

Technology Stack

Installation & Setup

Project Structure

Configuration Guide

Deployment

License

🚀 Features

🎨 Immersive UI/UX

Dynamic Hero Section: Features an HTML5 Canvas-based "neural network" background that reacts interactively to mouse movements.

Premium Dark Theme: A sophisticated Slate & Amber color palette designed for high contrast and luxury appeal.

Glassmorphism: Modern frosted glass effects on cards, navigation, and overlays.

Custom Cursor: A magnetic cursor with physics-based trailing effects (Desktop only) for a native-app feel.

Scroll Reveal Animations: Elements slide in, zoom, and fade gracefully as the user scrolls.

🛠️ Interactive Tools

Growth Estimator: A real-time JavaScript calculator allowing clients to estimate costs for followers/subscribers across Facebook, Instagram, TikTok, and YouTube.

Services Carousel: An auto-scrolling, touch-friendly slider showcasing expertise (Web Dev, SEO, etc.) with 3D tilt hover effects.

Data Visualization: Integrated Chart.js polar area and bar charts to visualize platform connectivity and pricing tiers.

📱 Fully Responsive

Adapts seamlessly to Mobile, Tablet, and Desktop screens.

Includes a custom mobile navigation menu and optimized touch targets.

🛠 Technology Stack

Core: HTML5, CSS3, Vanilla JavaScript (ES6+)

Styling: Tailwind CSS (loaded via CDN for instant usage)

Charts: Chart.js (v4.4.1)

Fonts: 'Plus Jakarta Sans' via Google Fonts

Icons: Inline SVG icons (Heroicons/Custom)

📦 Installation & Setup

Since this project uses CDN links, there are no dependencies to install.

Clone the Repository:

git clone (https://github.com/FarhanAliAbbasi/socialsphere.git)
cd social-sphere


Add Your Logo:

Place your logo image in the root folder.

Rename it to logo.png.

Note: The code handles sizing and fallback automatically.

Run Locally:

Simply double-click index.html to open it in your browser.

Optional: Use a Live Server extension in VS Code for hot-reloading during edits.

📂 Project Structure

social-sphere/
│
├── index.html                    # The main application file containing all code
├── logo.png                      # Your agency logo (required for nav bar)
└── README.md                     # This documentation file


⚙️ Configuration Guide

You can customize the dashboard by editing the index.html file directly. Look for the <script> section at the bottom.

1. Changing Calculator Rates

To adjust the cost per follower/subscriber:

Open index.html.

Search for the selectService function in the script.

Update the currentRate values or change the HTML data-rate attributes in the Growth Estimator section.

<!-- Example: Changing Facebook rate to 3.0 -->
<button ... data-rate="3.0" ... >Facebook</button>


2. Updating Contact Info

Scroll to the <footer> section in the HTML to update:

Phone Numbers: currently set to +92-314-950-0110 and +92-316-520-8030.

WhatsApp Link: Update the href in the floating button and footer links.

Social Links: Update href attributes for Facebook, Instagram, and TikTok icons.

3. Modifying Services

Locate the <section id="services">. Each service is a <div> block inside the slider. You can copy/paste these blocks to add more services or edit the text/images of existing ones.

Your site will be live at (https://farhanaliabbasi.github.io/socialsphere/)


📄 License

This project is open-source and available under the MIT License. You are free to use, modify, and distribute it for personal or commercial projects.

Social Sphere — Transforming Brands in the Digital Sphere.
