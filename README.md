# Clem's Gourmet Haven

A responsive, single-page restaurant website built with semantic HTML, CSS and vanilla JavaScript. It presents a restaurant's story, categorised menu, table reservation form and contact page, with no frameworks or build tools required.

## Overview

This project was developed as a front-end web development study in designing a complete, accessible small-business website. It demonstrates client-side view routing, tabbed content, form handling and responsive layout using only corAe web technologies.

## Features

- **Single-page navigation**: Home, About, Menu, Reservation and Contact views switched with hash-based routing (`hashchange`).
- **Tabbed menu**: Starters, Main Courses, Seafood, Pasta and Drinks, built with accessible tab and panel markup.
- **Reservation form**: Name, email, date, time and party size, with past dates blocked automatically.
- **Contact form**: Name, email, subject and message, with an on-page confirmation message.
- **Responsive design**: Mobile navigation toggle and a layout that adapts to different screen sizes.
- **Accessibility**: Semantic landmarks, ARIA-labelled sections and screen-reader-only headings.
- **Typography**: Khand typeface loaded from Google Fonts.

## Technologies

| Layer | Technology |
|-------|------------|
| Structure | HTML5 |
| Styling | CSS3 (embedded) |
| Behaviour | Vanilla JavaScript (ES5-compatible) |
| Fonts | Google Fonts (Khand) |

## Project Structure

```
Clem's Gourmet Haven/
├── index.html      # Markup, styles and scripts
├── assets/         # Images and logos
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<musksmith065-ship-it>/<clems-gourmet-haven-website>.git
   ```
2. Open the folder and double-click `index.html`, or use the **Live Server** extension in VS Code (right-click `index.html` → *Open with Live Server*).

No installation or build step is needed. An internet connection is required only to load the web font.

## Limitations and Future Work

- Forms currently show a confirmation message only; submissions are not sent anywhere. A backend or a form service would be needed to store or email them.
- Possible improvements: separate CSS and JS files, image optimisation, online ordering and multilingual support.

## Licence

Released under the [MIT License](LICENSE).

## Author

Created by Alfred Vandi. Feedback and suggestions are welcome through GitHub Issues.
