# Portfolio Project Guide

Single-page static portfolio website.

## Project Structure

- `index.html`: Complete layout, styling, and JavaScript logic.
- `public/`: Image assets used in the about and gallery sections.

## How To Run Locally

1. Open this folder in VS Code.
2. Open `index.html` in a browser (or use VS Code Live Server).

## How To Edit Content

1. Update text sections directly in `index.html`.
2. Replace images inside `public/`.
3. Keep image file names and letter case exactly the same as referenced in `index.html`.

## How To Edit Styling

1. Open the `<style>` block in `index.html`.
2. Adjust color variables in `:root` first for quick theme changes.
3. Update section-specific classes for layout and spacing.

## Form Behavior

The contact form is currently UI-only (`onsubmit="return false;"`) and does not send data to a backend service.

## Asset Compatibility Note

Some assets are `.HEIC`. If a browser does not render them correctly, convert those files to `.JPG` or `.PNG` and update the matching `src` paths in `index.html`.
