# Product Requirement Document
**Project:** Personal Professional Landing Page
**Owner:** Michaela N. Angus
**Course:** BAIS 3300 — Digital Product Management, The University of Iowa
**Date:** March 2026

---

## 01 — Problem Statement

Michaela N. Angus is a dual-degree student pursuing a B.B.A. in Finance and a B.B.A. in Business Analytics and Information Systems at the University of Iowa, graduating May 2026. She is returning to Northern Trust in Chicago as a full-time employee in July 2026.

A one-page resume communicates professional and educational experience, but it cannot convey personality, motivation, or direction. Michaela needs a personal landing page that shows *who she is* — what drives her, what she is curious about, and where she is headed — in a way that a static PDF cannot. The page positions her at the intentional intersection of finance and data analytics, making her dual-degree path feel like a strength rather than an undecided direction.

---

## 02 — Target Audience

**Primary audience:** Colleagues, managers, and partners at Northern Trust. As Michaela prepares to join the firm full-time, this page gives her team a richer understanding of her educational background, technical capabilities, and professional motivations before and after her start date. It sets context for who she is beyond her job title.

**Secondary audience:** Future recruiters and hiring managers in finance, wealth management, and analytics roles. Michaela is graduating in May 2026 and wants to keep her options open. The page will live publicly and remain accessible for future opportunities.

**What visitors are looking for when they arrive:**
- A clear sense of Michaela's capabilities and what she brings to a team
- Evidence of her analytical and financial skills through real project work
- An understanding of her motivations, curiosity, and professional interests
- Easy access to her contact information and professional profiles

---

## 03 — Goals & Success Metrics

| Goal | How We Measure It |
|------|-------------------|
| Page is live and publicly accessible before May 2026 graduation | URL resolves correctly on Azure Static Web App with custom domain |
| Page is linked in Michaela's email signature | Email signature updated with landing page URL within 1 week of launch |
| Primary audience at Northern Trust has viewed the page | At least one manager or partner at Northern Trust confirms they have visited the page within 30 days of starting |
| Page is shareable in professional contexts | URL is clean, loads quickly, and displays correctly on mobile and desktop |

---

## 04 — Required Content

### Hero Section
- **Must** display full name: **Michaela N. Angus**
- **Must** display professional tagline: *"Finance & Analytics Student | Curious, Driven, and Ready to Contribute"*

### Profile Photo
- **Must** include professional headshot (file: `IMG_1105.jpeg`, to be saved as `images/headshot.jpeg` in the project repo)

### Bio
- **Must** include a short bio covering:
  - Dual B.B.A. in Finance and Business Analytics & Information Systems, University of Iowa, graduating May 2026
  - GPA: 3.50/4.00 | Dean's List Fall 2022, Spring 2023
  - Returning full-time to Northern Trust, Chicago, July 2026
  - Motivated by the opportunity to solve problems and contribute to the success of a team and company
  - Passionate about understanding the "why" behind business processes, asking questions, taking initiative, and working at the intersection of finance and data analytics

### Skills
- **Must** include the following, organized into two groups:

**Tools:**
Python, SQL, Microsoft Excel, Microsoft PowerPoint, GitHub, Jupyter Notebook, Orange, Visual Studio Code

**Methodologies:**
Regression Analysis, Pivot Tables, Financial Forecasting, Correlation, Data Visualization/Manipulation, Optimization Modeling (Excel Solver)

### Projects
The page **must** feature the following three projects:

**Project 1 — IMDb & Box Office Analysis**
- **Must** include project title, tools, and outcome
- Tools: Python, Jupyter Notebook
- Description: Scraped and merged two datasets — IMDb Movie Ratings and Box Office Sales — to analyze and visualize the relationship between audience ratings and ticket sales revenue.

**Project 2 — Heart Attack Risk Data Mining**
- **Must** include project title, tools, and outcome
- Tools: Orange
- Description: Used data mining techniques to analyze health indicators (BMI, diabetes, hypertension, high blood pressure) and their relationship to heart attack risk. Found that elevated BMI and presence of conditions such as diabetes and hypertension were strong predictors of increased heart attack risk. Evaluated model performance using AUC.

**Project 3 — Aflac AI Synthetic Survey Project (In Progress)**
- **Must** include project title, tools, and outcome
- Tools: Python, Jupyter Notebook, web scraping
- Description: Working in a team of six as part of the Business Analytics and Information Systems Capstone to help Aflac implement AI-generated synthetic survey responses. The project scrapes and merges real customer reviews from platforms such as Yelp, Reddit, and Google Reviews to generate synthetic survey data, helping Aflac better understand customer sentiment and areas for improvement.
- **Should** note this is a live capstone project in progress

### Contact Section
- **Must** include LinkedIn: [linkedin.com/in/michaela-angus-42b321177](https://www.linkedin.com/in/michaela-angus-42b321177)
- **Must** include GitHub: [github.com/michaelaangus](https://github.com/michaelaangus)
- **Must** include email: michaela-angus@uiowa.edu
- **Should** display contact items as clearly labeled, clickable links opening in a new tab

> **Note:** Do not link to or embed a resume anywhere on this site. Resumes go stale quickly, and a live URL pointing to an outdated document does more harm than good. The landing page is a curated professional presence, not a resume mirror.

---

## 05 — Scope

| In Scope This Week | Out of Scope |
|--------------------|--------------|
| Single-page `index.html` site | Contact form (future iteration) |
| Hero section with name, tagline, and headshot | Blog or written articles |
| Bio paragraph | Dark mode toggle |
| Skills section (Tools + Methodologies) | Animations or scroll effects |
| Three project cards (IMDb analysis, Heart Attack mining, Aflac capstone) | Downloadable files of any kind |
| Contact section (LinkedIn, GitHub, email) | Resume link or embed |
| Deployment on Azure Static Web App | Multi-page site structure |
| GitHub repository with PRD.md and STANDARDS.md in root | Backend or server-side functionality |
| Connected to Replit for development | |

---

## 06 — Assumptions & Constraints

**Assets ready:**
- Professional headshot available (`IMG_1105.jpeg`)
- LinkedIn profile active: linkedin.com/in/michaela-angus-42b321177
- GitHub account active: github.com/michaelaangus
- Email confirmed for public display: michaela-angus@uiowa.edu

**Constraints:**
- Project is due imminently — scope must stay tight; one clean, complete page is the goal
- Development environment: Replit, connected to GitHub repository
- Hosting: Azure Static Web App with custom domain
- Skill level: Comfortable with HTML, CSS, and GitHub (desktop and web); familiar with VS Code
- Budget: No paid tools or frameworks — static site only
- The Aflac capstone project is ongoing; project description should reflect in-progress status

---

> **Next step:** Save this file as `PRD.md` in your GitHub repo root. Then open your `STANDARDS.md` template and use your PRD to fill in Section 1 (Project Overview) and Section 3 (Design Standards). Both files must be in your repository root before your first coding session.
