🚪 Sliding Door Reveal Activity Template

An interactive "sliding door" interface designed for progressive disclosure and step-by-step content discovery. This template utilizes draggable handles to physically "uncover" information, creating a tactile and engaging user experience for binary or sequential topics.

🚀 Live Demo

Explore the Sliding Door Interface Here

✨ Project Overview

The Sliding Door Reveal template is optimized for comparisons where "hiding" the content initially encourages active participation. It is ideal for "Before vs. After," "Problem vs. Solution," or "Phase 1 vs. Phase 2" scenarios.

Key Features

Tactile Sliding Mechanism: Dual interactive doors that can be dragged horizontally to reveal the text layers underneath.

Directional Versatility: Features two distinct sliding behaviors:

Left-to-Right Reveal: The cover retracts toward the left.

Right-to-Left Reveal: The cover retracts toward the right.

Branded Visual Identity:

Midnight Blue (#1f2a52): Used for high-contrast headers and the active handle hover state.

Accent Teal (#00bec7): The primary color for interactive handles to signal "draggability."

Light Aqua (#d2f0f0): The cover color, featuring a subtle "SLIDE TO REVEAL" watermark for user guidance.

Responsive Flex Layout: The interface automatically stacks the reveal sections vertically on mobile devices and aligns them side-by-side on desktops.

🛠️ Technical Implementation

Dynamic Positioning Logic: A custom JavaScript engine (setupRevealSlider) calculates real-time mouse/touch coordinates to update the width and left/right properties of the cover elements.

Touch-Ready Interaction: Fully supports touch events (touchstart, touchmove, touchend) with e.preventDefault() to ensure smooth dragging on mobile browsers.

State Management: The handles transition to a grabbing cursor and change color on interaction to provide immediate visual feedback.

Window Resize Handling: Includes a resetSlider listener to ensure the doors and handles correctly recalculate their boundaries if the browser window changes size.

📂 Project Structure

Sliding-Door-Reveal-Activity/
├── index.html          # Main application file (HTML/CSS/JS)
├── previews/           # Automated UI capture assets
└── .github/workflows/  # CI/CD for catalog and preview synchronization


🤖 Catalog Integration

This repository is part of the Catalog of Repos ecosystem. Automated workflows are configured to demonstrate the "open" and "closed" states of the doors for preview generation.

📄 License

MIT License - Created for the accounts-eles ecosystem.
