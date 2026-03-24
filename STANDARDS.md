# STANDARDS.md

## BAIS:3300 - Digital Product Management · Module 8 | Personal Landing Page Project

_This file contains technical instructions for this project. Every time you
begin a coding session, ask your LLM to read this file before writing any code.
The LLM will follow these standards automatically without you needing to repeat
them in every prompt._

_To start a session, paste this into your LLM:_
_"Please read my STANDARDS.md file before we begin. I will be asking you to build
and modify my personal landing page."_

---

## 1. Project Overview

This is a personal professional landing page for Michaela N. Angus, a dual-degree Finance and Business Analytics & Information Systems student at the University of Iowa, graduating May 2026. The page is designed for two audiences: her incoming team at Northern Trust in Chicago, where she returns full-time in July 2026, and future recruiters exploring her profile. A successful outcome is a clean, publicly accessible single-page site that conveys Michaela's personality, motivations, and capabilities at the intersection of finance and data analytics — something a resume alone cannot do.

---

## 2. Technical Standards

These rules apply to every file in this project without exception.

**Languages and versions:**

- HTML5 — use semantic elements throughout: `<header>`, `<main>`, `<section>`,
  `<article>`, `<footer>`, `<nav>`
- CSS3 — all styles must be written in `css/stylesheet.css`; no inline `style=""`
  attributes; no `<style>` tags in any HTML file
- HTML5 and CSS3 code must pass validation

**Folder structure:**

<pre>
/michaela-angus-landing (Root Folder)
├── index.html
├── PRD.md
├── STANDARDS.md
├── /css
│    └── stylesheet.css
├── /js
│    └── scripts.js
├── /images
│    └── headshot.jpeg
</pre>

**Framework:**

- No framework — vanilla CSS only

**Architecture:**

- Static site — no JavaScript frameworks, no server-side code, no database, no back-end
- Single `index.html` file in the project root
- External stylesheet: `stylesheet.css` in the css folder and referenced by relative path
- All images stored in the `images/` subfolder and referenced by relative path
  (e.g., `src="images/headshot.jpeg"`) — never link to external image URLs
- Do not link to or embed a resume anywhere on the site

**Responsiveness:**

- Fully responsive at all screen widths from 320px and wider
- No horizontal scrolling on any viewport

**Accessibility — WCAG 2.2 Level AA (non-negotiable):**

- All `<img>` elements must have a descriptive `alt` attribute
- Color contrast ratio: minimum 4.5:1 for normal text, 3:1 for large text
- Heading hierarchy must be logical: `<h1>` → `<h2>` → `<h3>`, no levels skipped
- All link text must be descriptive — no "click here", "read more", or bare URLs
- Page `<title>` element must be: `Michaela Angus | Finance & Analytics`
- All interactive elements (links, buttons) must be keyboard navigable

**Compatibility:**

- Must render correctly on Chrome, Safari, and Firefox; must be mobile-responsive (works on screens 375px and wider)

**Security:**

- Links to external sites should open in a new tab (`target="_blank"` with `rel="noopener noreferrer"`)

---

## 3. Design Standards

These visual rules apply to the entire site. Follow them on every build and every revision.

**Color palette:**

| Role                 | Hex Code  | Usage                                        |
|----------------------|-----------|----------------------------------------------|
| Background           | #FFFFFF   | Page background                              |
| Primary text         | #1A1A2E   | Body copy, paragraphs                        |
| Accent               | #0A2463   | Section headings, links, skill tags, nav     |
| Secondary background | #F0F4F8   | Section backgrounds, card backgrounds        |
| Accent hover         | #1E4D8C   | Link and button hover states                 |

**Typography:**

- Heading font: Inter — import from Google Fonts
- Body font: Inter
- Body size: 16px, line height: 1.6
- H1 (page name): 2.5rem, bold
- H2 (section headings): 1.5rem, bold, accent color (#0A2463)
- H3 (project titles): 1.1rem, bold
- Import line for `<head>`:
  `<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">`

**Imagery:** Professional headshot only. No stock photos or clip art. No emojis.

**Layout:**

- Maximum content width: 860px, centered on the page
- Navigation: sticky top bar with anchor links to each section (About, Skills, Projects, Contact)
- Section spacing: 72px top and bottom padding on each section
- Single column on mobile, two-column grid on desktop for project cards
- Generous whitespace throughout — clean and uncluttered

**Component styles:**

_Profile photo:_
- Circular crop, 180px diameter, centered in the hero section
- File: `images/headshot.jpeg`
- Alt text: `"Michaela Angus professional headshot"`

_Skill tags:_
- Rounded pill badges
- Tools: navy background (#0A2463) with white text
- Methodologies: light secondary background (#F0F4F8) with dark text (#1A1A2E)
- Font size: 0.85rem

_Project cards:_
- Light card background (#F0F4F8), subtle border-radius (8px)
- Display project title, tools used (as small tags), and a 2–3 sentence description
- Two-column grid on desktop, single column on mobile

_Contact links:_
- Display as labeled icon badges for LinkedIn, GitHub, and email
- Open in a new tab (`target="_blank"` with `rel="noopener noreferrer"`)
- Use text labels: "LinkedIn", "GitHub", "Email"

_Navigation links:_
- Plain text links, accent color (#0A2463) on hover, no underline by default
- Sticky top bar with white background and subtle bottom border

**Tone:**

- **Three words that describe the desired feel:** Professional, Approachable, Driven
- Clean and minimal. Professional but warm. Not a corporate brochure — a genuine snapshot of who Michaela is and what she brings.
- **Writing tone:** First person, direct, and confident. Avoid buzzwords. Lead with motivation and curiosity, not just credentials.

**Reference sites:**

- read.cv — for overall simplicity and whitespace
- brittanychiang.com — for section hierarchy and clean nav (light background version only)

---

_Remember: this document is a living artifact. Update it as your project evolves._
