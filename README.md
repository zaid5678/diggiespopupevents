# Diggies Pop Up Events

Static website for **Diggies Pop Up Events** — cocktail masterclasses, pop-up bars, and party entertainment.

## Pages

| File | Page |
|------|------|
| `index.html` | Home / Landing page |
| `about.html` | About Us |
| `services.html` | Services |
| `gallery.html` | Gallery |
| `contact.html` | Contact |

## Tech Stack

- Plain HTML5, CSS3, vanilla JavaScript — no build tools
- Google Fonts: Playfair Display + DM Sans
- Hosted on Netlify (static)

## Assets

| File | Description |
|------|-------------|
| `assets/logo.jpg` | Brand logo |
| `assets/intro.mp4` | Hero background video |

## Local Development

Open any `.html` file directly in a browser, or use a local server:

```bash
# Python 3
python3 -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Adding Gallery Photos

When photos are available, replace the placeholder `<div>` elements in `gallery.html` with `<img>` tags inside each `.gallery-item`:

```html
<div class="gallery-item">
  <img src="assets/gallery/event-name.jpg" alt="Description of the photo" loading="lazy">
</div>
```

Create an `assets/gallery/` folder and add images there. Recommended size: 1200×900px JPEG.

## Deployment

Push to GitHub and connect to Netlify. The `netlify.toml` handles publish directory and redirects.

```bash
git remote add origin https://github.com/zaid5678/diggiespopupevents.git
git push -u origin main
```

## Brand Colours

| Name | Hex |
|------|-----|
| Burgundy | `#6B1D2A` |
| Gold | `#D4A017` |
| Dark | `#2A0A10` |
| Cream | `#FAF6F0` |
