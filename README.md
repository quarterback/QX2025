<p align="center">
  <img src="assets/gh-banner.png" alt="QX2025 Banner">
</p>

<br/>
<div align="center">
  <a href="https://ronbronson.com">
    <img src="https://img.shields.io/badge/built_by-Ron%20Bronson-blue?style=flat-square" alt="Built by Ron Bronson" />
  </a>
  <a href="https://consequencedesign.org">
    <img src="https://img.shields.io/badge/read-more_at_consequencedesign.org-purple?style=flat-square" alt="Read more at consequencedesign.org" />
  </a>
</div>

<br/>

# QX2025 (Odyssey Fork)

**QX2025** is a minimalist publishing system for critical design writing, strategic foresight, and cultural theory. It is a heavily modified fork of the Odyssey Astro theme, rebuilt to host a growing archive of research, essays, and frameworks around consequence design, interface politics, and hype studies.

This site is built using [Astro](https://astro.build), focused on performance, legibility, and timeless web aesthetics. It’s meant for writing that endures—not for launch week hype.

## What's Different in This Fork?

- 🎨 **Custom Global Styles** – Rewritten global stylesheet using Google Fonts (`Martel`, `IBM Plex Mono`) for an editorial look with clear hierarchy.
- ✍️ **Content-First Philosophy** – Designed for longform text, citations, and structured writing over flashy marketing blocks.
- 🧠 **Integrated Theoretical Frameworks** – Built to showcase critical research projects like Interface Memetics, Crisis Cascades, and Consequence Design.
- 📚 **Speculative Design Focus** – Not a startup boilerplate. This fork is optimized for thought leadership, cultural criticism, and systems thinking.

## Setup

```bash
git clone https://github.com/quarterback/QX2025.git
cd QX2025
npm install
npm run dev
```

Then open [http://localhost:4321](http://localhost:4321) in your browser.

## Customizing

Start by editing the site metadata in `src/config/settings.js`:

```js
export default {
  title: `Out of Scope`,
  description: `Writing at the edge of consequence, interface, and institutional design.`,
  url: `https://consequencedesign.org`, // Or wherever you deploy
  name: `QX2025`,
  enableThemeSwitcher: false,
};
```

Then swap out global styles in `src/styles/global.css` and edit nav items via `src/config/nav.js`.

## Deploy

You can deploy this to [Netlify](https://netlify.com), [Vercel](https://vercel.com), or any static host.

Here’s how to build for production:

```bash
npm run build
```

Then follow [Astro’s deployment guide](https://docs.astro.build/en/guides/deploy/) for your platform of choice.

## Credit

This fork was originally based on the [Odyssey Astro Theme](https://github.com/treefarmstudio/odyssey-theme) by [Jaydan Urwin](https://twitter.com/jaydanurwin). Major thanks to them for open sourcing a clean, extensible theme.

