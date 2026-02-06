Premium Neumorphic Slider Clock

A minimalist, high-fidelity digital clock inspired by modern Neumorphic (Soft UI) design and mechanical vertical sliders. This project reimagines time-telling through tactile, staggered vertical bars that respond dynamically to the current time.

✨ Features

Unique Vertical Slider Logic: Unlike standard clocks, the bars (tracks) move vertically while the indicator remains fixed, mimicking high-end mechanical hardware.

Tactile Neumorphic UI: Utilizes complex shadow layering to create depth, simulating physical materials and ambient lighting.

Staggered Bar Layout: Replicates the "un-aligned" aesthetic where bar height is determined by the digit's value (0-2 for hours, 0-9 for ones, etc.).

Smart Light/Dark Mode: A seamless transition between a soft indigo-tinted light theme and a deep charcoal dark theme.

Dynamic Lens Effect: Numbers scale and fade as they approach the central focal point to create a sense of optical focus.

Fully Responsive: Adapts gracefully to mobile, tablet, and desktop viewports.

Vanilla Implementation: Zero dependencies. Built purely with HTML, CSS, and JavaScript.

🚀 Getting Started

Since this is a single-file application, running it is simple:

Clone the repository:

git clone [https://github.com/cadubarboss/neumorphic-slider-clock.git](https://github.com/cadubarboss/neumorphic-slider-clock.git)

Open clock.html in any modern web browser.

Or Go to https://slider-clock.vercel.app/

🛠️ Technical Details

Design Language

Typography: Uses the geometric sans-serif Montserrat for a clean, industrial look.

Shadows: Uses dual-source box shadows (light/dark) to create the signature "extruded" and "recessed" neumorphic shapes.

Physics: The transitions use a custom cubic-bezier(0.3, 1.6, 0.4, 1) to provide a "spring-loaded" mechanical snap.

Key Logic

The application uses a centered horizontal alignment axis. Instead of moving the "thumb" of the slider, the JavaScript calculates the necessary translateY for each bar based on the current time digit to ensure the active number is perfectly centered within the dark indicator circle.

🎨 Customization

You can easily tweak the appearance by modifying the CSS variables in the :root and body.dark-mode sections:

:root {
    --bg-color: #e6eef9;
    --shadow-light: #ffffff;
    --shadow-dark: #b8c6d9;
    --date-color: #5a67d8;
}


📜 License

Distributed under the MIT License. See LICENSE for more information.

Inspired by the principles of Soft UI and tactile digital interfaces.
