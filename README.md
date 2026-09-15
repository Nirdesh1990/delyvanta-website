# DELYVANTA — Website

A single-file, self-contained website for DELYVANTA (digital services for local merchants).

## What's inside

- `index.html` — the entire website (HTML + CSS + JS in one file, no build step, no dependencies to install)
- `.vscode/` — recommended editor settings and extensions

## How to open this in VS Code

1. Unzip this folder anywhere on your computer.
2. Open VS Code → **File → Open Folder** → select the unzipped `delyvanta-website` folder.
3. If prompted to install the recommended extension (**Live Server**), click **Install**.

## How to preview the site

**Option A — Live Server (recommended)**
1. Install the "Live Server" extension by Ritwick Dey (VS Code will prompt you automatically).
2. Right-click `index.html` in the file explorer → **Open with Live Server**.
3. The site opens in your browser and refreshes automatically when you save changes.

**Option B — Just open the file**
- Double-click `index.html`, or right-click → **Open in default browser**. No server needed since the page has no backend calls.

## Editing content

Everything lives in `index.html`:
- Text content is in the HTML body — search for section comments like `<!-- HERO -->`, `<!-- PRICING -->`, `<!-- CONTACT -->` to jump to a section.
- Colors and fonts are defined once at the top of the `<style>` block under `:root { ... }` — change a value there and it updates everywhere.
- Phone number and email appear in a few places (header, hero, pricing, contact section) as `tel:` and `mailto:` links — update all instances if these ever change.

## Deploying / hosting

This is a fully static site — it can be hosted for free on:
- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

Just upload `index.html` (no build step required).
