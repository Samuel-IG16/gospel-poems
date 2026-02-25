# GospelPoems

A platform for gospel poetry — where faith meets verse.

Live site featuring the anthology of **Pastor John Igbinijesu**, an ordained minister of the Gospel and resident Pastor of Word Assembly Beulah House Center. Built as the public face of a growing platform for gospel poets worldwide.

---

## Pages

| File | Description |
|---|---|
| `index.html` | Platform landing page — hero, mission, featured writer, poem previews, email sign-up |
| `Gospel Poem.html` | Author profile — bio, stats, category cards |
| `Jesus.html` | 13 poems themed around Jesus Christ |
| `Holy Spirit.html` | 13 poems themed around the Holy Spirit |
| `Christianity.html` | 7 poems themed around Christianity |
| `Weightiermatters.html` | 11 poems themed around Weightier Matters |
| `Benediction.html` | Closing benediction page |

## Tech Stack

- **HTML5 / CSS3** — static site, no build step required
- **Bootstrap 5.3.3** — loaded via jsDelivr CDN
- **Google Fonts** — Playfair Display, Lora, Inter
- **Formspree** — email sign-up form (no backend required)

## Design System

| Token | Value |
|---|---|
| Primary background | `#0d1b2a` (deep navy) |
| Accent | `#c9a227` (warm gold) |
| Light background | `#f9f6f1` (cream) |
| Heading font | Playfair Display |
| Body / poem font | Lora |
| UI font | Inter |

## Local Development

No build tools needed. Just open any `.html` file in a browser, or serve the folder with any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .
```

## Email Sign-up (Formspree)

The join form on `index.html` uses [Formspree](https://formspree.io). The endpoint is already configured. To use a different account:

1. Sign up at formspree.io
2. Create a new form and copy the endpoint URL
3. Replace the `action` attribute value in the `<form>` tag inside `index.html`

## Author

**Pastor John Igbinijesu** — igbinijesujohn@gmail.com

## Developer

**Samuel Igbinijesu** — exenexmedia@gmail.com

---

*"I write Gospel Poems to reach others for Christ." — Pastor John Igbinijesu*
