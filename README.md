# Kuyet Andrew | Virtual Assistant

Personal portfolio website for **Kuyet Andrew**, a virtual assistant offering administrative support, customer support and social media management.

**Live site:** [rohi-andrew.vercel.app](https://rohi-andrew.vercel.app)

## Contact

- **Email:** [kuyetrohiandrew@gmail.com](mailto:kuyetrohiandrew@gmail.com)
- **WhatsApp:** [+234 702 652 0260](https://wa.me/2347026520260)
- **LinkedIn:** [Kuyet Andrew](https://www.linkedin.com/in/kuyet-andrew-203346313)

## What is in this project

| File | Purpose |
| --- | --- |
| `index.html` | The whole website: Home, About, Services and Contact views, with all styles and scripts inside |
| `cv.pdf` | Her CV, linked from the "Download CV" buttons |
| `og.jpg` | Preview image shown when the link is shared on WhatsApp, LinkedIn and social media |
| `README.md` | This file |

## How the site works

It is a single static HTML file with no build step. The four "pages" are views inside `index.html`, and the nav switches between them using the address hash (`#home`, `#about`, `#services`, `#contact`), so each view can be linked to directly.

## Deploying on Vercel

1. Put `index.html`, `cv.pdf` and `og.jpg` at the top level of the repository.
2. Import the repository into [Vercel](https://vercel.com) and deploy. No framework or build settings are needed.
3. Open `/cv.pdf` on the live site to confirm the CV loads.

If a deploy is blocked, check that the Git commit email matches the one on your GitHub account.

## Editing

- **Text and sections:** edit `index.html` directly.
- **CV:** replace `cv.pdf` and keep the filename exactly `cv.pdf` (lowercase, no numbers).
- **Share preview:** replace `og.jpg` with a 1200 x 630 image. WhatsApp may cache the old preview for a while.

## Design

Black background with navy, teal, amber and coral accents. Headings use Bricolage Grotesque and body text uses Source Sans 3, both loaded from Google Fonts.
