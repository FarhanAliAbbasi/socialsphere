Social Sphere - Interactive Digital Agency Dashboard

Social Sphere is a high-performance, single-page interactive website designed for a modern digital marketing agency. Built with a focus on immersive user experience, it features advanced animations, interactive data visualization, and a premium dark-themed aesthetic.

🚀 Live Demo Features

Immersive Hero Section: Features a dynamic, interactive HTML5 Canvas background representing a social network graph that reacts to mouse movement in real-time.

Smart "Growth Estimator": A fully functional JavaScript calculator that allows potential clients to estimate costs for social media growth across different platforms (Facebook, Instagram, TikTok, YouTube).

Data Visualization: Integrated Chart.js polar area and bar charts to visualize platform connectivity and pricing structures dynamically with custom animations.

Interactive Services Carousel: A responsive, auto-scrolling slider showcasing services (Web Dev, SEO, App Dev) with 3D tilt effects, cinematic hover animations, and sequential scroll reveal.

Scroll Reveal Animations: Custom intersection observer logic that triggers smooth entry animations (fade-in, slide-in, zoom) as the user scrolls down the page.

Premium UI/UX:

Glassmorphism: Frosted glass effects on cards and navigation.

Custom Cursor: A magnetic cursor with physics-based trailing effects (Desktop only).

Dark Mode: A sophisticated slate & amber color palette designed for high contrast and readability.

Responsive Design: Fully adaptive layout that works seamlessly on mobile, tablet, and desktop devices.

🛠️ Technologies Used

HTML5: Semantic structure.

Tailwind CSS (via CDN): Utility-first styling for rapid, responsive design and animations.

Vanilla JavaScript: Core logic for animations, state management, calculator functions, and DOM manipulation (No framework required).

Chart.js: For rendering interactive data charts.

Google Fonts: Utilizing 'Plus Jakarta Sans' for modern typography.

📂 Project Structure

This project is contained within a single, portable HTML file for easy deployment.

social-sphere/
│
├── social_sphere_dashboard.html  # Main application file
├── logo.png                      # Agency logo (optional, auto-fallback provided)
└── README.md                     # Project documentation


⚙️ Configuration & Customization

1. Logo Setup

Place your company logo in the root directory and name it logo.png. The dashboard is configured to automatically load this file. If missing, it falls back to a stylized "S" icon.

2. Contact Information

Search for the footer section in social_sphere_dashboard.html to update:

Phone numbers

WhatsApp links

Social media profiles (Facebook, Instagram, TikTok)

3. Pricing & Calculator Logic

To modify the rates for the Growth Estimator:

Open social_sphere_dashboard.html.

Locate the selectService function script.

Update the data-rate attributes on the buttons to change the cost per unit (e.g., data-rate="2.0" for 2 PKR/follower).

4. Gemini AI Integration (Optional)

The code contains a placeholder for Google's Gemini API to power the "AI Content Strategist" feature (currently disabled/removed for the static version). To re-enable:

Uncomment the AI section in the HTML.

Add your API key to the const apiKey = "" variable in the script.

📦 How to Run

Clone the repository:

git clone [https://github.com/yourusername/social-sphere.git](https://github.com/yourusername/social-sphere.git)


Open the file:
Simply double-click social_sphere_dashboard.html to open it in Chrome, Firefox, Safari, or Edge.

🚀 Deployment

Since this is a static HTML file, it can be deployed instantly to:

GitHub Pages: Go to Settings > Pages > Source (main branch).

Netlify/Vercel: Drag and drop the folder into the dashboard.

Designed to showcase the intersection of creativity and technology.
