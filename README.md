# Personal Blog Website

A clean, minimalist personal blog website built with hand-coded HTML and CSS for a UMD course project.

## Folder Structure

```
personal-blog/
├── index.html          # Home page - blog posts and introduction
├── about.html          # About Me page - personal info and interests
├── resume.html         # Resume page - education, experience, skills
├── discover-umd.html   # Discover UMD page - video embed and highlights
├── contact.html        # Contact page - form and contact info
├── styles.css          # Single external stylesheet for all pages
├── team-video.mp4      # Team marketing video (add your file here)
├── images/
│   ├── campus.jpg      # Blog post image (campus scene)
│   ├── studying.jpg    # Blog post image (studying)
│   ├── duluth.jpg      # Blog post image (Duluth/Lake Superior)
│   └── profile.jpg     # Profile photo for About page
└── README.md           # This file
```

## How to Open / Run

1. Download or clone this folder to your computer.
2. Open `index.html` in any web browser (Chrome, Firefox, Safari, Edge).
3. Use the navigation bar to move between pages.
4. No server, build step, or installation is required — it's all static HTML and CSS.

## For Hosting (GitHub Pages)

1. Push this folder to a GitHub repository.
2. Go to Settings > Pages > set source to "main" branch.
3. Your site will be live at `https://yourusername.github.io/repo-name/`.

## Code Walkthrough

### HTML Structure
- **5 pages**, each as a separate `.html` file.
- Every page shares the same layout: navigation bar, hero header, main content area, and footer.
- Semantic HTML elements are used throughout (`<nav>`, `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- Comments mark each major section for easy reading.

### CSS (`styles.css`)
- **One external stylesheet** linked by all pages — keeps styling consistent and avoids repetition.
- Organized into clearly labeled sections: reset, navbar, hero, content, cards, resume, contact form, footer, and responsive breakpoints.
- Uses a **neutral color palette** (black `#1a1a1a`, white, grays) with a modern sans-serif font stack.
- **Responsive design** using CSS media queries at 768px and 480px breakpoints. The navigation collapses into a hamburger menu on smaller screens.
- CSS Grid is used for the blog card layout and contact page; Flexbox is used for navigation and the about page layout.

### JavaScript
- Minimal JS: a single `toggleMenu()` function handles the mobile hamburger menu. No frameworks or libraries.

### Design Choices
- **Minimalist aesthetic**: clean lines, generous whitespace, subtle hover effects.
- **Accessibility**: semantic HTML, sufficient color contrast, form labels, and alt text on images.
- **No dependencies**: everything is self-contained — no CDN links, frameworks, or build tools required.
