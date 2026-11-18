# Tink-Her-Hack 3.0 — HTML, CSS & JS Session

Code from the beginner web development session I took for **[Tink-Her-Hack 3.0](https://tinkerhub.substack.com/i/156688308/tink-her-hack-30)** (2025), TinkerHub's women-only hackathon and Kerala's largest. The class was online. In it we built a small profile-card page from scratch to cover the basics of the web's three core languages:

- **HTML** for structure
- **CSS** for styling
- **JavaScript** for interactivity

## What we built

A profile card with a photo, a name, a short bio and a link to a second page, plus a button that changes the page's background color when you click it.

## Project structure

```
.
├── index.html        # Main page with the profile card and the button
├── login.html        # Blank second page used to show linking between pages
├── images/
│   └── img.jpg       # Profile photo
├── styles/
│   └── index.css     # All the styling
└── scripts/
    └── index.js      # Click handler for the color-change button
```

## Concepts covered

### HTML
- Basic document structure: `<!DOCTYPE html>`, `<head>`, `<body>`
- Common elements: `<div>`, `<img>`, `<h3>`, `<p>`, `<a>`, `<button>`
- Attributes: `id`, `class`, `src`, `alt`, `href`
- Linking external CSS (`<link>`) and JS (`<script defer>`)
- Inline styles compared with external stylesheets
- Links between pages (`index.html` → `login.html`)

### CSS
- Selectors: element (`body`), id (`#my-profile`) and class (`.photo`, `.name`, `.bio`)
- Colors with `rgb()` and named colors
- The box model: `padding`, `margin`, `border`, `width`, `height`
- **Flexbox** layout: `display: flex`, `flex-direction`, `justify-content`, `align-items`, `gap`
- Centering content on the page with `height: 100vh`
- Rounded corners and circular images with `border-radius`
- The `:hover` pseudo-class

### JavaScript
- Selecting elements with `document.getElementById`
- Event listeners (`addEventListener('click', ...)`)
- Changing styles from JS (`element.style.backgroundColor`)

## Running it

You don't need to install or build anything. Either:

1. Clone the repo and open `index.html` in your browser, or
2. Use the **Live Server** extension in VS Code for automatic reloads while you edit.

```bash
git clone https://github.com/nandhu-44/THH-HTML-CSS-JS.git
```

> **Note:** the "Go to login" link uses an absolute path (`/login.html`). It works with Live Server or any local server, but not when you open the file straight from disk (`file://`). Change it to `login.html` if you want it to work both ways.

## Try it yourself

Some ideas for practising after the session:

- Build out `login.html` with a form (`<form>`, `<input>`, `<label>`)
- Make the button toggle between colors instead of only setting red
- Add social links or a skills list to the profile card
- Make the card responsive so it looks good on mobile

## About Tink-Her-Hack

Tink-Her-Hack is a women-only hackathon run by [TinkerHub](https://tinkerhub.org/), a Kerala-based community that helps people learn by building. The third edition, **Tink-Her-Hack 3.0**, ran in early 2025 as an 18-hour hackathon hosted at campuses across Kerala. Around three-quarters of the participants were beginners, most of them first-year students.

To get beginners ready to build, participants had Study Jams, online learning sessions like this one, and mentor guidance before the hackathon.
