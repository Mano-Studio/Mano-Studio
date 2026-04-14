# Mano Studio — Project Rules

## What this project is
A web design portfolio for Mano Studio. Single HTML files, all CSS inline in <style> tags, no frameworks, no build tools.

## File structure
- index.html — Mano Studio homepage
- osteria-nora.html — demo site 1
- flor-rama.html — demo site 2
- palau-properties.html — demo site 3
- bar-bravo.html — demo site 4
- images/ — all image assets

## Rules — never break these
- All CSS lives in a <style> tag in the head. No external CSS files.
- No JavaScript frameworks. Vanilla JS only when needed.
- No border-radius except where explicitly specified.
- All colors defined as CSS variables at the top of every file.
- Every section has a commented class name.
- All pages link back to index.html with a fixed bottom-left "← Mano Studio" link.
- Mobile responsive on all pages.

## Mano Studio brand colors
--bg: #F5F0EA
--text: #1A1814
--accent: #C0A889

## When I ask you to change something
Only change exactly what I ask. Do not refactor, restructure, or improve anything else.
