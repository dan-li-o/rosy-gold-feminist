# Rosy Gold Feminist Scholar Template

A single-page HTML template that showcases the work of a feminist scholar in a rosy-gold palette. The layout highlights biography, featured works, research themes, media appearances, and mentorship opportunities in a warm, editorial style.

Live preview: https://dan-li-o.github.io/rosy-gold-feminist/

## Getting Started

1. Make sure you have a free GitHub account (the walkthrough below shows every click).
2. Grab the template files by downloading the ZIP or forking the repo.
3. Follow the GitHub Pages click-through steps to publish, then open `index.html` to start customizing.

No build tools are required; everything runs from static files.

## No-Code Setup Walkthrough

### 0. Create your free GitHub account

1. Visit [github.com/signup](https://github.com/signup) and follow the prompts.
2. Pick a username you are happy to make public—it becomes the basis of your default site URL (`https://YOUR-USERNAME.github.io`).
3. Enter your email address, create a password, and complete the quick puzzle verification.
4. When GitHub asks about plans, choose **Individual → Free**.
5. Open the confirmation email from GitHub and click the verification link; your account is inactive until you do.

### 1. Grab the template files

Choose whichever route feels most comfortable. Each option gives you the exact same files.

#### Download a ZIP (recommended for non-coders)

1. Click the green **Code** button on this repository.
2. Choose **Download ZIP**.
3. Unzip the download—you’ll get a folder with `index.html`, `styles.css`, `script.js`, `.nojekyll`, and this README.

#### Fork in the browser (keeps a synced copy on GitHub)

1. While signed into GitHub, click **Fork** (top-right of the repository page).
2. Accept the defaults and press **Create fork**.
3. You now have your own copy under your account and can edit files directly on GitHub.com.

#### Clone with Git (optional, for command-line users)

```bash
git clone https://github.com/YOUR-USERNAME/rosy-gold-feminist.git
cd rosy-gold-feminist
```

### 2. Publish with GitHub Pages (Click-Through Only)

1. In GitHub, create a new **public** repository named `YOUR-USERNAME.github.io` (match your username exactly).
2. Open that empty repository and choose **Add file → Upload files**.
3. Drag-and-drop `index.html`, `styles.css`, `script.js`, `.nojekyll`, and any images or assets you want to include.
4. Scroll down and click **Commit changes** to store the upload.
5. Go to the repo’s **Settings** tab, then select **Pages** in the left sidebar.
6. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
7. For **Branch**, pick `main` and the `/ (root)` folder, then press **Save**.
8. Wait 1–2 minutes. GitHub Pages deploys automatically and shows the live URL at the top of the Pages settings screen.

The bundled `.nojekyll` file tells GitHub to serve everything exactly as you uploaded it—no extra processing required.

## Project Structure

- `index.html` — Page markup with comment callouts guiding custom content swaps.
- `styles.css` — Global styles, color palette, typography, layout rules, and scroll-reveal animation styling.
- `script.js` — Lightweight IntersectionObserver helper that animates sections as they enter the viewport (respects reduced-motion settings).
- `.nojekyll` — Tells GitHub Pages to serve the files as-is (no Jekyll processing or asset renaming).
- `assets/` — (Optional) place self-hosted images, SVGs, or downloads you want to bundle with the site.

## Edit Checklist

Open `index.html` in any text editor and move through the sections in order:

- **Hero (header):** Update the name, tagline, and CTA button text/URL. Swap the background image URL in `styles.css` if you prefer a different photo.
- **About:** Replace the bio paragraphs with your story and swap the portrait image. The circular crop works best with centered portraits around 800×800px.
- **Featured Works:** Each `<article class="book">` represents a project or publication. Replace the Unsplash links with your own cover art and adjust the title, publisher, and summary copy.
- **Research Themes:** Edit the headings and blurbs, duplicate `<div class="card">` blocks for more themes, or remove ones you do not need (keep the opening and closing `<div class="grid">` tags).
- **Media & Talks:** Update the placeholder URLs, titles, and descriptions. Each list item uses `data-reveal-delay` so you can stagger animations if desired.
- **Mentorship:** Rewrite the two cards and the note to reflect your advising or community work.
- **Contact:** Swap in your preferred email address and newsletter or booking link.
- **Footer:** Adjust the year, name, or credit line as needed (please keep the Danlio Studio credit if you can).

## Customization Tips

- **Colors:** Update the CSS custom properties at the top of `styles.css` to shift the rosy-gold palette or tweak the subtle gold border accents.
- **Typography:** Replace the Google Fonts in the `<head>` of `index.html` or adjust font stacks as needed.
- **Hero image:** Swap the link in the `.hero` background for symbolic or portrait photography that matches your scholar.
- **Book covers:** Replace the current dummy book cover images with your own artwork or design assets.
- **External links:** Replace sample URLs (e.g., newsletter signup, talk recordings, publication archive) with live destinations, if you need them.
- **Sections:** Duplicate or remove the provided sections to match your scholar's priorities. Each section is self-contained for easy rearranging.
- **Animations:** Tweak or remove the `data-reveal` attributes in `index.html`, or set custom delays with `data-reveal-delay="0.1s"` to fine-tune the scroll cadence.
- **AI assist:** You can paste any of the files into an AI assistant (ChatGPT, Claude, etc.) and ask for rewrite suggestions, color swaps, or new section ideas—then apply the suggested edits manually.

## Update & Maintenance

1. Preview locally by double-clicking `index.html`; your browser will open the page instantly.
2. When you make edits, upload the changed files to the same GitHub repository and commit—GitHub Pages redeploys automatically within a minute.
3. Keep the `.nojekyll` file in place so Pages continues to serve the site without modification.
4. Want version history? Make small commits (e.g., “Update hero bio”) so you can restore previous content if needed.

## Troubleshooting

- **Page shows 404:** Confirm the repository name is exactly `YOUR-USERNAME.github.io` and that GitHub Pages is set to deploy from `main` and the root folder.
- **Images not loading:** Ensure the image URLs are correct. If you upload files, match the filename and capitalization used in your HTML.
- **Changes not appearing:** Hard refresh (`Cmd+Shift+R` on macOS or `Ctrl+Shift+R` on Windows) or wait a minute for GitHub’s CDN to update.
- **Animations feel too strong:** Remove the `data-reveal` attributes or disable the IntersectionObserver logic by deleting `script.js` and the `<script>` tag in `index.html`.
- **Need a clean copy of a section:** Grab the original markup from this repository and paste it over your version, then reapply your content edits.

## Credits

Design concept by Danlio Studio. Background imagery and book covers reference royalty-free assets from Unsplash.
