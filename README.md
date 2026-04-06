# ema-ilic-portfolio

A simple static portfolio/consulting landing page.

## Files

- `index.html` - the live page

## Recommended free hosting: GitHub Pages

Why GitHub Pages over Tiiny Host:
- free
- stable
- connected to git/GitHub
- easy to update later
- keeps version history

## How to edit the site

Open `index.html` in any editor and change the text, links, prices, or sections.

Common edits:
- headline text → search for `Everyone is talking about AI.`
- prices → search for `€200`, `€1,500`, `€4,500`
- Stripe links → search for `buy.stripe.com` / `book.stripe.com`
- email → search for `ema.ilic9@gmail.com`
- WhatsApp → search for `385993749704`
- Medium / LinkedIn links → search for `medium.com` / `linkedin.com`

## Preview locally

Option 1: just open `index.html` in your browser.

Option 2: run a tiny local server:

```bash
cd ema-ilic-portfolio
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Publish with GitHub Pages

From the repository root:

```bash
git add index.html
git commit -m "Update portfolio page"
git push origin main
```

Then in GitHub:

1. Open the repository settings
2. Go to **Pages**
3. Set source to **Deploy from a branch**
4. Select branch: `main`
5. Select folder: `/ (root)`
6. Save

GitHub will give you a public URL (for example `https://<your-username>.github.io/ema-ilic-portfolio/` if you use a project site).

### Renamed the repository on GitHub?

If you renamed the remote from something else to `ema-ilic-portfolio`, point your local clone at the new URL:

```bash
git remote set-url origin https://github.com/<your-username>/ema-ilic-portfolio.git
```

(Use SSH instead if that is how you clone.)

## Updating the live page later

After changing `index.html`:

```bash
git add index.html
git commit -m "Update portfolio copy"
git push origin main
```

GitHub Pages will redeploy automatically.

## If you prefer Tiiny Host instead

1. Zip the contents of this folder (`index.html` and any assets)
2. Upload at <https://tiiny.host>
3. Re-upload whenever you change the page

This is simpler at first, but worse for versioned updates than GitHub Pages.
