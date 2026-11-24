# Personal Portfolio Website

**Course Assessment:** HTML & CSS Practical Assessment: Personal Portfolio Website  
**Time Limit:** 3 Hours  
**Max Marks:** 100  
**Target Profile:** First-Year Engineering Student (B.Tech Computer Science & Engineering)  
**Developer:** Swaraj N (`swarajn556`)  
**Technologies:** Semantic HTML5, Modern CSS3 (Zero JavaScript)

---

## 📋 Project Overview

This repository contains a responsive, accessible, and high-performance Personal Portfolio Website designed and developed as an individual practical assessment. The website showcases technical skills, academic coursework, and engineering projects while adhering strictly to **pure HTML5 and CSS3** (without any JavaScript).

---

## 🗂️ Project Structure

```text
personal-portfolio/
│
├── index.html                   # Semantic HTML5 document containing all portfolio sections
├── style.css                    # External CSS3 stylesheet with variables, Flexbox & Grid
├── README.md                    # Project documentation & assessment compliance report
│
└── assets/
    └── images/
        ├── profile.svg          # Vector profile avatar with glowing frame & student badges
        ├── project1.svg         # Visual preview mockup for Portfolio Project
        ├── project2.svg         # Visual preview mockup for CGPA Calculator Project
        └── project3.svg         # Visual preview mockup for Campus Wayfinder Project
```

---

## ✨ Features & Rubric Requirements Compliance

### 1. Header & Navigation
- [x] Displays personal logo `<SN /> Swaraj.dev` with hover effects.
- [x] Navigation links: **Home**, **About**, **Skills**, **Projects**, and **Contact**.
- [x] All anchor links (`#home`, `#about`, `#skills`, `#projects`, `#contact`) navigate cleanly.
- [x] Alignment styled using **CSS Flexbox** (`display: flex; justify-content: space-between`).
- [x] Smooth underline animation and hover feedback on links.

### 2. Hero / Home Section
- [x] Welcome greeting badge: `👋 Welcome to My Portfolio`.
- [x] Name prominently displayed: `Swaraj N` with gradient text effect.
- [x] Short introduction defining first-year engineering background.
- [x] Profile image with circular gradient glow, border, and floating badges.
- [x] Prominent **"Contact Me"** and **"Explore Projects"** call-to-action buttons.
- [x] Quick engineering stats display (1st Year B.Tech, 8+ Skills, 3+ Projects).

### 3. About Section
- [x] Introduction highlighting enthusiasm for software engineering and foundational computer science.
- [x] Educational background timeline (B.Tech in CSE 2024-2028, Higher Secondary PCMC 92%).
- [x] Detailed interests (Frontend architecture, algorithms, open-source) and career aspiration (Full-Stack Software Engineer).
- [x] Three-column responsive grid layout with hover elevation.

### 4. Skills Section
- [x] Displays at least 5 technical & professional skills (HTML5, CSS3, C Programming, Python, Git & GitHub, Problem Solving).
- [x] Illustrated using interactive cards, category badges, and colored progress bars (`width: %`).
- [x] Additional competencies cloud (Responsive Design, Data Structures, VS Code, Technical Documentation).

### 5. Projects Section
- [x] Showcases 3 engineering & web development projects (exceeding the minimum requirement of 2):
  1. **Responsive Personal Portfolio** (HTML5, CSS3, Flexbox & Grid)
  2. **Engineering CGPA & Grade Predictor** (C Language, Algorithms, CLI)
  3. **Smart Campus Wayfinder Guide** (HTML5, CSS Grid, UI/UX)
- [x] Includes project titles, detailed descriptions, key highlight checkmarks, and tech tags.
- [x] Responsive visual SVG preview placeholders for every project.
- [x] Interactive hover zoom on images and card elevation.

### 6. Contact Section & Form
- [x] Contact information panel (Email: `swarajn556@gmail.com`, Location, Academic status, social pills).
- [x] Form fields:
  - **Full Name** (`type="text"`, `required`, `minlength="2"`)
  - **Email Address** (`type="email"`, `required`)
  - **Subject** (`type="text"`, `required`, `minlength="4"`)
  - **Message** (`<textarea>`, `required`, `rows="5"`, `minlength="10"`)
  - **Submit Button** (`type="submit"`)
- [x] Native HTML5 validation triggers when attempting to submit empty or malformed fields.
- [x] Custom focus ring states and `:invalid` focus styling.

### 7. Footer
- [x] Personal brand name and copyright information: `© 2026 Swaraj N. All Rights Reserved.`
- [x] Functional social media links (GitHub, LinkedIn, Email).
- [x] "Back to Top" navigation link returning to `#home`.

### 8. Styling, Layout & Responsiveness
- [x] External stylesheet `style.css` linked in `<head>`.
- [x] Comprehensive design token system via CSS Custom Properties (`:root`).
- [x] CSS Flexbox and CSS Grid implemented throughout.
- [x] Interactive transitions & hover animations on buttons, cards, links, and images.
- [x] Fully responsive across desktops, tablets (≤ 992px), mobile devices (≤ 768px), and small screens (≤ 480px).
- [x] Zero horizontal scrolling (`overflow-x: hidden`, `box-sizing: border-box`).
- [x] **Strictly NO JavaScript** used in any part of the project.

---

## 🧪 Verification & Mandatory Test Cases Matrix

| Test Case | Expected Result | Status |
|:---|:---|:---:|
| Website opens successfully | Clean rendering of layout without broken elements | PASS |
| All navigation links work | Scrolls smoothly to `#home`, `#about`, `#skills`, `#projects`, `#contact` | PASS |
| All required sections visible | Header, Hero, About, Skills, Projects, Contact, Footer | PASS |
| At least 5 skills displayed | 6 primary skills with progress bars + 7 badge items | PASS |
| At least 2 project cards displayed | 3 comprehensive project cards with visual mockups | PASS |
| Contact form has all required fields | Name, Email, Subject, Message, Submit Button | PASS |
| Empty fields trigger validation | Browser displays native "Please fill out this field" tooltip | PASS |
| Images load correctly | High-definition SVG assets load offline without broken links | PASS |
| Hover effects active | Nav links underline, buttons scale/glow, cards elevate | PASS |
| Responsive on mobile & desktop | Adapts fluidly with no horizontal overflow | PASS |
| External CSS file linked | `style.css` linked via `<link rel="stylesheet">` | PASS |
| No JavaScript policy | 0 `<script>` tags, zero external JS libraries | PASS |

---

## 🚀 How to Run Locally

1. Open a terminal in the project directory:
   ```bash
   cd personal-portfolio
   ```
2. Open `index.html` directly in your default browser:
   - On Windows:
     ```powershell
     Start-Process "index.html"
     ```
   - Or open using VS Code Live Server extension.

---

## 💻 Opening in VS Code

To open this project in Visual Studio Code:
```powershell
code .
```

---

## 🌐 Publishing to GitHub

To push this repository to your GitHub account:

```bash
# 1. Initialize local git repository (if not already done)
git init -b main

# 2. Stage and commit all files
git add .
git commit -m "feat: complete HTML & CSS portfolio website assessment"

# 3. Create a new repository on GitHub named 'personal-portfolio'
# 4. Link your local repo to GitHub and push:
git remote add origin https://github.com/swarajn556/personal-portfolio.git
git push -u origin main
```
