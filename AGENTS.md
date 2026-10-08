# Repository Guidelines

## Project Structure

This is a small static website for SICHAE, a startup developing an automation control software platform. `index.html` contains the page content and all CSS in one file so it can be edited directly. `logo.svg` is the editable vector logo asset. Keep future images in a clearly named `assets/` directory; until approved images are available, use the page's `Coming Soon` placeholders.

## Development

No build tools, package manager, or JavaScript framework are required. Open `index.html` directly in a browser to view the site, or serve the folder with any static file server. Keep page styling in the `<style>` block in `index.html` and avoid adding dependencies for simple interactions or layout changes.

## Content and Style

The page is written in Korean and uses semantic HTML sections with IDs for navigation. Preserve the responsive CSS in the same file. Use clear Korean copy, concise section headings, and consistent blue, cyan, and white colors. Describe the platform as in development; do not present planned features as released or verified. Keep technical claims within the capabilities provided by the company and confirm new claims before adding them. Update the page title and description if the company name or positioning changes.

## Images and Contact Details

Use `Coming Soon` wherever project photos, equipment images, or public case materials are not ready. The contact email is `admin@sichae.com`; keep the visible address and `mailto:` target in sync if it changes.

## Changes

Keep commits focused and use short imperative messages, such as `Add automation services section`. For pull requests, summarize the visible changes and include a screenshot when the page layout changes substantially. There is no automated test suite; check the page in a browser at desktop and mobile widths before publishing.
