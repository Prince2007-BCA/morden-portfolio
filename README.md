Prince Kushwaha | Creative Technologist Portfolio

A highly advanced, single-file HTML portfolio featuring a "Dark Mode" aesthetic, Glassmorphism design, and interactive elements. This project is built for performance and visual impact, using vanilla JavaScript and Tailwind CSS without the need for a complex build process.

🌟 Key Features

Dynamic Visuals:

Particle Canvas Background: Interactive network animation that reacts to mouse movement.

Custom Cursor: Magnetic, lagging cursor effect for a premium feel (hidden on touch devices).

Glassmorphism: Frosted glass effects on navigation and cards using backdrop filters.

Animations:

Scroll Reveal: Elements smoothly fade and slide up as they enter the viewport.

Infinite Marquee: Continuous scrolling text for the technology stack.

Hover Effects: 3D transforms and glow effects on interactive elements.

Play Arena (Minimax AI):

A fully functional Tic-Tac-Toe game embedded directly in the portfolio.

Unbeatable AI: Uses the Minimax algorithm to ensure the AI never loses (Win or Draw only).

Regional Personality: Features custom status messages ("Ka ho khela", "Ka ho kareja har gaila").

Responsive Design: Fully fluid layout that adapts to mobile, tablet, and desktop screens.

🛠️ Technologies Used

HTML5: Semantic structure.

Tailwind CSS (CDN): Utility-first styling for rapid UI development.

Vanilla JavaScript: Logic for canvas, game AI, custom cursor, and scroll observers.

Lucide Icons: Lightweight, consistent SVG icons.

Google Fonts: "Outfit" and "Space Grotesk" for typography.

🚀 Getting Started

Since this project is contained within a single HTML file and uses CDNs for libraries, no installation or build server is required.

Download: Save the index.html file to your computer.

Run: Double-click index.html to open it in your default web browser.

📝 Customization Guide

You can edit the index.html file directly in any text editor (VS Code, Notepad++, Sublime Text).

1. Personal Information

Search for "Prince Kushwaha" to find and replace the name.

Nav Logo: Line 155

Hero Section: Line 185

About Section: Line 230

2. Images

The portfolio currently uses Dicebear API for the avatar.

Avatar: Search for api.dicebear.com (Line 227) and replace the src URL with your own image path.

3. Projects

Locate the <section id="projects"> (Line 257).

Each project is wrapped in a <div> with the class bento-card.

Replace the text descriptions, titles, and icons to match your actual work.

4. Game Messages

To change the regional dialect messages in the Tic-Tac-Toe game:

Search for statusElement.innerText inside the <script> tag.

Start Message: "Ka ho khela" (Line 595 & 649)

Loss Message: "Ka ho kareja har gaila" (Line 615)

5. Colors

The project uses Tailwind's configuration in the <head> to define colors.

colors: {
    dark: '#0a0a0a',
    primary: '#6366f1', // Indigo
    accent: '#a855f7',  // Purple
    danger: '#ef4444',  // Red
}


Change the hex codes in the tailwind.config script block (Line 25) to alter the theme globally.

📄 License

This project is open-source and available for personal and commercial use.
