# MindAI Product Landing Page

A responsive landing page concept for **MindAI**, a fictional AI-powered learning companion. Built with HTML, CSS, and vanilla JavaScript. This is the coded companion to the UI/UX design assignment; recreate the layout in Figma to submit the required design file.

## Target audience
Students, creators, early-career professionals, and lifelong learners who want approachable AI support for learning and problem-solving.

## Design choices
- **Visual direction:** friendly, polished, optimistic, and technology-focused.
- **Color palette:** deep ink `#1F1B2D`, purple `#7655E8`, pale lavender `#F1EDFF`, mint `#D9F6E9`, and warm white `#FBF9F6`.
- **Typography:** Space Grotesk for headings and DM Sans for body copy.
- **Layout:** roomy desktop two-column hero, three feature cards, dark workflow section, testimonial, CTA, and footer.
- **Responsive behavior:** desktop/tablet/mobile breakpoints; feature cards stack on mobile; navigation becomes a toggle menu.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser, or use VS Code with the Live Server extension.
3. Internet is only needed to load Google Fonts. The page otherwise uses local HTML/CSS/JS.

## Figma build guide
Create a desktop frame at **1440 × 2400 px** and a mobile frame at **390 × 3200 px**. Use a 12-column desktop grid with 80 px side margins and 24 px gutters. Use 16 px mobile side margins.

### Suggested design tokens
- Ink: `#1F1B2D`
- Muted text: `#716D80`
- Primary purple: `#7655E8`
- Purple hover: `#5E3BD0`
- Lavender: `#F1EDFF`
- Mint: `#D9F6E9`
- Warm white: `#FBF9F6`
- Border: `#ECE8F3`
- Headings: Space Grotesk, Bold/Semibold
- Body: DM Sans, Regular/Medium/Semibold

### Suggested Figma Auto Layout settings
- Header: horizontal, space between, center aligned, 24 px gap, 32 px horizontal padding.
- Hero: horizontal on desktop, vertical on mobile, 48 px gap; text and visual each fill available width.
- CTA/button: horizontal, center aligned, 12 px vertical and 20 px horizontal padding, 12 px radius, 12 px gap.
- Feature cards: vertical, 20 px gap, 24 px padding, 18 px radius.
- Feature grid: horizontal with 20 px gaps on desktop; vertical on mobile.
- Footer: horizontal with wrapping or stacked rows on mobile.

## Reusable components to create in Figma
1. Primary Button (default and hover variants)
2. Feature Card
3. Navigation Link (default and active variants)
4. Optional: Brand Logo, Lesson Row, Testimonial Author

## GitHub submission
1. Create a new public repository named `mindai-landing-page`.
2. Upload `index.html`, `styles.css`, `script.js`, and `README.md` (or push the extracted folder with Git).
3. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for GitHub Pages to publish. Your website URL will look like `https://YOUR-USERNAME.github.io/mindai-landing-page/`.
5. Submit the repository URL and, if requested, the live website URL in your class Google Sheet.
6. Share your Figma design URL separately if the sheet asks for the actual design.

> Important: A coded website is not a replacement for the assignment's Figma deliverables. Make sure to create the frames, reusable components, Auto Layout, shared color/text styles, and short design rationale in Figma.

## Design rationale (can adapt for submission)
MindAI is designed for students and curious early-career learners who need a supportive way to learn and solve problems. Purple communicates creativity and intelligence, while mint and warm neutrals keep the experience approachable. A clear headline, one primary action, compact social proof, three scannable feature cards, and a numbered workflow help visitors understand the value quickly. Auto Layout and reusable components make spacing consistent and the design easier to adapt to mobile screens.
