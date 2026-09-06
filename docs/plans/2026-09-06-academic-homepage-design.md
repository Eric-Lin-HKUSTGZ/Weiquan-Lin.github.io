# Weiquan Lin Academic Homepage Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Build a polished, responsive, GitHub Pages-ready academic homepage for Weiquan Lin.

**Architecture:** Use a dependency-free static site with one semantic HTML document, one CSS file, and one small JavaScript file. The page follows the Academic Pages information architecture: a sticky horizontal masthead, a left author profile/sidebar, and a right academic content column containing About, News, Research Interests, Publications, Experience, Awards, and Education.

**Tech Stack:** HTML5, CSS3, vanilla JavaScript, Google Fonts with local fallbacks.

---

### Task 1: Build the Academic Pages content structure

**Files:**
- Create: `index.html`

**Steps:**
1. Add a top masthead and left author profile with avatar, role, interests, location, email, and GitHub.
2. Add compact academic sections for About, News, Research Interests, Publications, Experience, Awards, and Education.
3. Use only resume-supported facts; avoid inventing paper links, citation counts, or acceptance decisions.
4. Add responsive-friendly landmarks and accessible labels.

### Task 2: Establish the visual system

**Files:**
- Create: `styles.css`

**Steps:**
1. Define white background, neutral text, light borders, and academic blue link tokens.
2. Implement the desktop masthead, two-column profile/content layout, lists, publication entries, and mobile layout.
3. Keep motion limited to smooth scrolling and a responsive menu so the visual hierarchy remains academic.
4. Verify typography, contrast, focus states, and overflow at narrow widths.

### Task 3: Add small interactions

**Files:**
- Create: `script.js`

**Steps:**
1. Implement mobile menu toggling.
2. Highlight the active navigation section with IntersectionObserver.
3. Add current year and pointer glow behavior with a reduced-motion guard.

### Task 4: Verify the page

**Files:**
- Verify: `index.html`, `styles.css`, `script.js`

**Steps:**
1. Run a local static server and inspect the page in a browser at desktop and mobile widths.
2. Check that all navigation anchors work and no console errors occur.
3. Review the rendered result for clipping, unreadable text, broken image behavior, and reduced-motion accessibility.
