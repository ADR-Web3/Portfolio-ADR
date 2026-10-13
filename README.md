# Aduragbemi Aleem — Portfolio

Plain HTML and CSS. No framework, no build step.

## Files

| File | Page |
|---|---|
| `index.html` | Home |
| `work.html` | Case studies and writing samples |
| `about.html` | Bio, experience, skills, education |
| `contact.html` | Contact details and form |
| `styles.css` | Shared styles for every page |

## Before you publish

1. **Fill every yellow placeholder.** Search the files for `class="ph"`. Replace the whole `<span class="ph">…</span>` with your real text, or delete the line if you don't have the information.
2. **Add your photo** as `images/ADR.jpeg` (the same path your current site uses).
3. **Add your CV** as `cv.pdf` in the same folder as `index.html`.
4. **Set up the contact form.** Create a free form at formspree.io and replace `YOUR_FORM_ID` in `contact.html`, or delete the form and keep the email link.
5. **Writing samples** on `work.html`: replace each `href="#"` with the article's URL.

## Deploying

- **Vercel or Netlify:** upload this folder as a new project. No settings needed.
- **Keeping your current Next.js site:** give these files to your developer. The content, structure and styles can be moved into the existing project page by page.

If you move off `adr-portfolio-omega.vercel.app` (to your own domain, for example), update the `canonical` and `og:url` links at the top of each HTML file.
