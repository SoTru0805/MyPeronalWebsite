<<<<<<< HEAD
# Thanh Son Truong — Personal Portfolio Website

A dark, tech-themed personal portfolio website built with vanilla HTML, CSS, and JavaScript. Showcases projects, skills, and experience as a full-stack IT student based in Melbourne, Australia.

---

## Live Preview

> Deploy to GitHub Pages, Netlify, or Vercel and paste your URL here.

---

## Project Structure

```
portfolio/
├── index.html       # Main HTML structure and page content
├── style.css        # All styles, layout, animations, and responsive rules
└── README.md        # Project documentation
```

---

## Features

- Sticky navigation bar with active section highlighting on scroll
- Animated hero section with key stats
- About section with highlights grid
- Skills section organised by category (Languages, Frameworks, Mobile, Database, etc.)
- Featured project case studies (Optimise Your Wellbeing, WeatherWear, FlavourHub, Santorini)
- Additional projects grid
- Experience timeline split by Industry and Technical Practice
- Contact section with links to Email, LinkedIn, and GitHub
- Fade-in scroll animations throughout
- Fully responsive layout for mobile and desktop

---

## Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Markup     | HTML5                             |
| Styling    | CSS3 (custom properties, grid, flexbox) |
| Scripting  | Vanilla JavaScript (IntersectionObserver) |
| Fonts      | Space Mono, DM Sans (Google Fonts) |
| Hosting    | GitHub Pages / Netlify / Vercel   |

No frameworks, no build tools, no dependencies — just two files.

---

## Getting Started

### Run locally

1. Clone or download this repository:
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   ```
2. Open `index.html` in your browser — no server or build step required.

### Deploy to GitHub Pages

1. Push both files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Set the source to the `main` branch, root folder.
4. Your site will be live at `https://yourusername.github.io/repository-name`.

### Deploy to Netlify

1. Drag and drop the project folder onto [netlify.com/drop](https://netlify.com/drop).
2. Your site goes live instantly with a public URL.

---

## Customisation

### Update personal details

Open `index.html` and update the following:

| What                | Where to find it                                    |
|---------------------|-----------------------------------------------------|
| Your email          | `<a href="mailto:thanhson@email.com">`              |
| LinkedIn URL        | `<a href="https://linkedin.com/in/thanhsontruong">` |
| GitHub URL          | `<a href="https://github.com/thanhsontruong">`      |
| Hero availability   | `<div class="hero-tag">Available for opportunities` |
| Footer year/city    | `<footer>` at the bottom of the file               |

### Change the accent colour

Open `style.css` and update the `--accent` variable in `:root`:

```css
:root {
  --accent: #00e5a0;   /* change this to any colour you like */
}
```

### Add a project

Copy one of the existing `.project-card` blocks in `index.html` and update the title, description, stack tags, and highlights. For smaller projects, copy a `.mini-card` block instead.

---

## Sections

| # | Section    | Description                                              |
|---|------------|----------------------------------------------------------|
| — | Hero       | Name, tagline, CTAs, and quick stats                     |
| 1 | About      | Bio and four key differentiators                         |
| 2 | Skills     | Tech stack organised into six categories                 |
| 3 | Projects   | Four featured case studies + four mini project cards     |
| 4 | Experience | Industry/team experience and technical practices         |
| 5 | Contact    | Email, LinkedIn, GitHub links                            |

---

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). The `backdrop-filter` blur effect on the nav may not render in older Firefox versions — it degrades gracefully with no visual breakage.

---

## License

This project is personal and not licensed for reuse. Feel free to use it as inspiration, but please build your own design rather than republishing this one directly.

---

*Built by Thanh Son Truong · Melbourne, AU*
=======
# MyPeronalWebsite
Personal portfolio website built with vanilla HTML, CSS &amp; JavaScript. Features project case studies, skills, and experience as a full-stack IT student based in Melbourne.
>>>>>>> d6fed0e76f41fcc1f0b565259406eaffa6bee60e
