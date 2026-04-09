# Prompt: Build an Interactive Website from practical-narrative.md

You are building a single-page interactive website from the file `practical-narrative.md` in this directory. Read the entire file first. Understand its structure, arguments, references, and data before writing any code.

## What This Document Is

A set of working notes making three claims about AI, structured as Parts 1-3:

- **Part 1: The Talking Library** — AI is a compressed amalgam of human knowledge made conversational. The conversational interface triggers social cognition, creating overtrust, attachment, inability to calibrate, and generification of thinking.
- **Part 2: The Taxonomy of Multiplication** — AI multiplies along five axes that can point in opposite directions simultaneously. There's a shadow side to every multiplication, a jagged frontier nobody can see, and we're stuck in Phase 1 of adoption.
- **Part 3: Agency Is Upstream** — Your agency is the only judgment in the system. The enchantment-determinism double illusion makes it easy to stop steering.

The document is dense with references, data points, tables, and enriched explanations. Your job is to make all of this navigable and readable without losing depth.

## Design Principles

### 1. Lightness First, Depth on Demand

The main reading experience should be **light** — clean text, clear structure, no walls of reference explanations. But every reference, data point, and technical term should have depth available on interaction:

- **References**: Every bolded reference in the document (e.g., "**Ted Chiang — 'ChatGPT Is a Blurry JPEG of the Web' (The New Yorker, 2023)**") should appear in the main text as a compact citation. The full enriched explanation (the paragraph that follows each reference) should appear as a **hover tooltip / popover** on desktop or **tap-to-expand** on mobile. The reader sees the claim; they can access the evidence without it cluttering the flow.

- **Technical terms and concepts**: Terms like "anthropomimesis," "reckoning vs. judgment," "jagged frontier," "enchanted determinism," "moral crumple zones," "general-purpose technology," "stochastic parrots" — these should have short **inline definition tooltips** on hover/tap. Write these definitions yourself based on how the document explains them.

- **Tables**: The document has several tables (three-layer claim tables, fragments table, five axes, shadow table, agency requirements table, enchanted determinism table). These should be **styled as clean, readable components** — not raw markdown tables. Consider whether any are better presented as interactive cards, comparison layouts, or structured lists rather than literal tables.

### 2. Visualizations — Think, Then Build

Read through the entire document and identify where a visualization would communicate something **better than text**. Do not add visualizations decoratively. Each one should earn its place.

Places to seriously consider:

- **The Five Axes (Part 2)**: These are dimensions with opposing directions (volume↑ quality↓, novice↑ expert↓, etc.). A visual that shows paired axes with actual data points from the text could be powerful. Think about how to show that "AI multiplication is a vector, not a scalar" — maybe a radar chart, maybe parallel axes, maybe something custom.

- **The Jagged Frontier (Part 2, Axis 5)**: This is about an irregular, unpredictable boundary between where AI helps and where it hurts. The document says "the frontier cuts across human categories of difficulty in ways that don't match how we think about our own work." Visualize this — an irregular, jagged boundary across a task landscape, showing that "easy" tasks can be outside the frontier and "complex" tasks inside it. Make the point visually that intuition about task difficulty doesn't predict AI helpfulness.

- **The Shadow Table (Part 2)**: The multiply/divide pairs could be a visual — each row showing the two sides of the same coin.

- **David's Three Phases (Part 2)**: A simple timeline or progression showing Phase 1 → 2 → 3 with a "you are here" marker.

- **The Enchanted Determinism table (Part 3)**: Two illusions working together. Could be a visual showing how enchantment and determinism combine.

- **The Self-Reinforcing Loop (not yet in the document but implied by the structure)**: Parts 1, 2, and 3 reinforce each other. If you see this pattern after reading, consider visualizing the loop — library-as-mind → unmapped multiplication → agency abdication → back to library-as-mind.

For each visualization, use D3.js, SVG, or clean CSS — whatever fits best. Subtle animations are fine where they aid comprehension. No gratuitous motion.

### 3. Dark Mode / Light Mode

- Auto-detect system preference via `prefers-color-scheme`
- Include a manual toggle in the top-right corner
- Persist the manual choice in a CSS class on the body (no localStorage — just session state)
- Both themes should be carefully designed — dark mode is not just "invert the colors." Use appropriate contrast ratios, muted accent colors, and readable typography in both modes.

### 4. Typography and Layout

- Use a clean serif or humanist sans-serif for body text. This is intellectual content, not a SaaS landing page.
- Maximum content width ~700px for readability
- Generous line height (1.6-1.7)
- Clear visual hierarchy: Part titles > Section headers > Subsection headers > Body text
- Margin notes or side annotations are welcome if they aid navigation
- The document has three parts — consider a subtle fixed navigation (sidebar or top bar) showing which part the reader is in

### 5. Navigation and Structure

- The three Parts should feel like chapters — distinct sections with clear transitions
- A table of contents at the top (or sidebar) that tracks reading position
- Smooth scroll between sections
- Each Part begins with "The Claim" in a visually distinct blockquote or callout style — these are Ivan's original words and should stand out as the anchoring statements

### 6. Mobile

- Everything should work on mobile
- Tooltips become tap-to-expand on touch devices
- Visualizations should be responsive or have mobile-appropriate alternatives
- Tables should not require horizontal scrolling — restructure them for narrow screens if needed

## Technical Constraints

- Single HTML file with embedded CSS and JS
- You may use D3.js (CDN) for visualizations
- No React, no build step, no framework
- Clean, semantic HTML
- All content comes from practical-narrative.md — do not invent new claims or add references not in the document

## Process

1. Read the entire practical-narrative.md file carefully
2. Plan the information architecture — what becomes main text, what becomes tooltip/popover, what becomes visualization
3. Write the HTML/CSS/JS
4. Review: does every section read cleanly without expanding anything? Does the depth exist for those who want it? Do the visualizations communicate their point?

## What Success Looks Like

A reader should be able to:
- Read through the entire argument in 15-20 minutes without feeling overwhelmed
- Hover/tap on any reference to understand who said what and why it matters
- See the data visually where numbers and relationships matter
- Switch between dark and light mode seamlessly
- Navigate between parts easily
- Come away understanding three claims, how they connect, and why they matter for how you use AI
