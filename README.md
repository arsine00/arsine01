# Kihyun Kim — Academic Profile Website

A responsive, six-page personal academic website for **arsine00.github.io**. Built with standard HTML, CSS, and a small amount of JavaScript; no build tools or dependencies needed.

## Pages
- `index.html` — Home
- `research.html` — Research
- `publications.html` — Publications (deliberately no fabricated records)
- `experience.html` — Experience & Education
- `cv.html` — Curriculum Vitae
- `contact.html` — Contact

## Deploy to GitHub Pages

1. Sign in to GitHub as `arsine00`.
2. Create a **public** repository named **`arsine00.github.io`** (exactly).
3. Upload all website files **at the repository root**, preserving the `assets/` directory. You can use **Add file → Upload files** to drag and drop everything inside this project folder.
4. Commit the upload to the default `main` branch.
5. Open **Settings → Pages** → **Build and deployment → Source: Deploy from a branch** → **Branch: main / (root)** → **Save**.
6. Visit **https://arsine00.github.io/** after GitHub Pages completes publishing. If deploying under another repo name, relative links still work but the site URL is `https://arsine00.github.io/REPOSITORY/`.

## Customize before sharing
- Add a verified email address to `contact.html` if you want to make one public.
- Replace the empty publication section in `publications.html` with verified citations and links.
- In `cv.html`, to enable a PDF download after adding `assets/Kihyun_Kim_CV.pdf`, insert:
  `<a class="btn primary" href="assets/Kihyun_Kim_CV.pdf" download>Download CV ↗</a>`
- Edit research descriptions as needed, particularly any unpublished project details you prefer not to publish.
- Change the profile text and educational dates as needed across HTML pages.
- Typography uses Google Fonts online (Manrope, DM Sans), falling back to installed sans-serif fonts offline.
- The scientific helix is an original decorative SVG embedded in HTML; it is not presented as a literal tRNA secondary structure.

## Preview locally
Open `index.html` in a browser, or in the project directory run `python -m http.server 8000` and visit `http://localhost:8000/`.

## Privacy
The site contains no contact email, home address, unpublished sequence data, or fabricated scholarly records. Please review all research descriptions before making the repository public.
