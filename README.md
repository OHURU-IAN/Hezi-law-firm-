# Hesbon Odhiambo Law Firm — Website

A multi-page, responsive marketing site for a law firm, built with **semantic HTML, modern CSS and a little vanilla JavaScript**. It uses no frameworks or build step.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)

## Pages

| Page | File | Content |
| --- | --- | --- |
| Home | `index.html` | Hero, practice-area overview, about section, contact call to action |
| Services | `services.html` | Litigation, compliance and advisory services |
| Team | `team.html` | Attorney profiles |
| Contact | `contact.html` | Contact details and enquiry form |

## Implementation

- **Layout:** CSS Grid and Flexbox, with breakpoints at 768px and 520px for tablet and mobile.
- **Theming:** brand colours are defined once as CSS custom properties (`--navy`, `--gold`, `--slate`, …) in `styles.css` and reused everywhere.
- **Typography:** Playfair Display for headings, Oswald for accents.
- **Accessible navigation:** the mobile menu toggle updates `aria-expanded` and `aria-controls`, and decorative icons are marked `aria-hidden`.
- **No dependencies:** one shared stylesheet and a small inline script (menu toggle and footer year).

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

## Roadmap

- Connect the contact form to a form backend (for example Formspree or a serverless function)
- Replace placeholder social links
- Add Open Graph and meta tags for SEO and link previews
- Deploy to GitHub Pages
