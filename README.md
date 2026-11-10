# lea-landing-page

A single-page landing site for **Learning English Academy (LEA)**, a spoken-English training pack delivered online through Telegram. The page content is in French.

## What it is

A static, framework-free page built with plain HTML, Tailwind CSS and a little vanilla JavaScript. It is meant to present the training offer and let visitors choose a plan.

## Sections

- Hero with the main promise and call-to-action buttons
- What learners will master
- Who the training is for (students, professionals, traders)
- 3-month programme (Foundations, Communication, Mastery)
- Trainers
- Pricing (two plans)
- FAQ (native `<details>` elements)
- Final call-to-action, footer and a payment modal

## Tech stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com) via CDN
- [Font Awesome](https://fontawesome.com) 6 via CDN
- Google Fonts (Inter)
- Vanilla JavaScript for the modal, copy-to-clipboard and smooth scrolling

No build step and no dependencies to install.

## Run it locally

1. Clone the repository:
   ```bash
   git clone https://github.com/mbmos/lea-landing-page.git
   cd lea-landing-page
   ```
2. Open `index.html` in a browser, or serve the folder with any static server (for example the VS Code Live Server extension or `python -m http.server`).

## Project files

- `index.html`: the landing page
- `index-new.html`: another version of the page
- `LANDING_PAGE_COPY.md`, `IMPROVEMENTS_SUMMARY.md`: working notes (in French)

## Notes

- Tailwind is loaded from its CDN, which is convenient for prototyping. For production, compile Tailwind locally.
- Contact details and payment information in the page belong to the academy. Replace them with your own if you reuse this template.

## Status

Personal project, work in progress. Issues and suggestions are welcome.
