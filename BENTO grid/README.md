Advanced Bento Grid: Fintech UI Implementation
A high-fidelity, responsive feature dashboard built with CSS Grid (12-row resolution) and Nested Flexbox. This project demonstrates advanced layout control, content alignment, and semantic architecture.

🚀 Technical Evolution
Initially designed as a 5-row grid, this project evolved into a 12-row coordinate system to allow for precise asymmetrical box heights and custom alignment points ("Line A" and "Line B" logic).

🧠 Key Engineering Concepts Mastered:
High-Resolution Grid Mapping: Utilizing grid-template-rows: repeat(12, 1fr) to provide granular control over card spans and vertical offsets.

Nested Flexbox Architecture: Implementing flex-direction: row on cards with internal flex-direction: column wrappers to separate text groups from illustrations.

CSS Typography & Spacing: Leveraging line-height: 1.8 for readability and resetting default browser margins (margin: 0) to achieve tight, "Bento-style" spacing.

Box-Model Mastery: Using box-sizing: border-box and overflow: hidden to ensure content integrity within fixed viewport heights (90vh).

Semantic Grouping: Applying multiple-selector logic (e.g., .box1 h2, .box1 p { ... }) to write DRY (Don't Repeat Yourself) and maintainable CSS.

🛠️ Tech Stack
HTML5: Semantic grouping with <article> and <div> content wrappers.

CSS3: Advanced Grid, Flexbox, and custom track sizing.

Git: Atomic commits and version history management.

🧩 Architecture Deep-Dive
The 12-Row Coordinate System
By doubling the row density, the layout achieves a specific "Squeezed" middle section for secondary features while allowing primary features to dominate the vertical space.

CSS
/* Achieving precise Line A and Line B positioning */
grid-template-rows: repeat(12, 1fr);
grid-template-areas:
    "box1 box1 box1 box2 box2 box2 box2" /* Rows 1-3: Header Focus */
    "box1 box1 box1 box3 box3 box4 box4" /* Rows 4-7: The "Squeeze" */
    "box5 box5 box5 box5 box6 box6 box6";/* Rows 8-12: Footer Focus */
Media Object Pattern (Flexbox Nesting)
To prevent text and images from clashing, content was wrapped in div containers, allowing for independent alignment of headings and paragraphs within a horizontal flex container.

📂 Project Structure
Plaintext
BENTO-grid/
├── Images/             # Optimized SVG/PNG illustrations
├── index.html          # Semantic HTML structure
├── bentogrid.css       # Advanced Grid & Flexbox logic
└── README.md           # Technical documentation

