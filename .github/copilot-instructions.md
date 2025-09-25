# Copilot Instructions

This is a simple, static landing page for a product called "Omega".

## Project Overview

- **Framework**: None. This is a plain HTML, CSS, and JavaScript project.
- **Structure**: The entire site is contained in `index.html`.
- **Styling**: Styling is primarily handled by [Tailwind CSS](https://tailwindcss.com/), included via a CDN. There are also some custom inline styles in the `<head>` of `index.html` for the background image and font.
- **Assets**: Images are located in the `/Images` directory.
- **JavaScript**: A small, inline JavaScript snippet in `index.html` handles a number-counting animation for the stats section when it becomes visible on the screen. It uses the `IntersectionObserver` API.

## How to work with this codebase

- **No Build Step**: Since this is a static site with no build process, you can open `index.html` directly in a browser to see your changes.
- **Styling**: To add or change styles, use Tailwind CSS utility classes directly in the HTML elements. For major style changes that can't be achieved with Tailwind, consider adding them to the inline `<style>` block in `index.html`.
- **JavaScript**: Any new JavaScript functionality can be added to the existing `<script>` tag at the bottom of `index.html` or in a new separate `.js` file if the logic becomes more complex.
