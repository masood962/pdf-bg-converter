# PDF Dark to Light Converter

**Free online tool to convert dark-background PDFs to white background with black text.**

> Perfect for Made Easy, Vision IAS, coaching notes, and any lecture slides with dark backgrounds.

🔗 **Live Demo:** https://yourusername.github.io/pdf-bg-converter/

---

## Features

- ✅ White background + dark black text conversion
- ✅ Remove top-right logo / watermark
- ✅ Remove side black stripes and bottom border
- ✅ Choose page range (e.g. only convert pages 5–30)
- ✅ Boost contrast for crisp printing
- ✅ 100% free, no sign-up, no server uploads
- ✅ Works entirely in your browser

---

## How to deploy on GitHub Pages (free hosting)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it: `pdf-bg-converter`
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the file
1. Click **Add file** → **Upload files**
2. Drag and drop `index.html` into the box
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: `main`, folder: `/ (root)`
4. Click **Save**

### Step 5 — Your site is live!
After ~2 minutes, your site will be live at:
```
https://yourusername.github.io/pdf-bg-converter/
```
Replace `yourusername` with your actual GitHub username.

---

## Update the URLs in index.html

Before uploading, open `index.html` and replace all instances of:
```
yourusername
```
with your actual GitHub username. Search for it — it appears in the og:url, og:image, canonical link, and footer.

---

## How it works

1. **Upload** — Select a dark PDF (stays on your device, never uploaded)
2. **Configure** — Choose page range and toggle options
3. **Convert** — Each page is processed pixel-by-pixel in the browser
4. **Download** — Get your clean, printer-friendly PDF

---

## For Google to find your site (SEO)

After your site is live:

1. Go to [Google Search Console](https://search.google.com/search-console)
2. Add your site URL
3. Submit your sitemap (or just the URL)
4. Google usually indexes within 1–2 weeks

The `index.html` already includes:
- SEO meta tags and description
- Open Graph tags (for sharing on WhatsApp/social)
- Structured data (JSON-LD) for Google
- Relevant keywords in title and description

---

## Tech stack

- Pure HTML + CSS + JavaScript (no frameworks, no build tools)
- [PDF.js](https://mozilla.github.io/pdf.js/) — renders PDF pages to canvas
- [jsPDF](https://github.com/parallax/jsPDF) — assembles output PDF
- Canvas API — pixel-level image processing

---

## License

MIT — free to use, modify, and share.
