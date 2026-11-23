# Hustle Bee

A responsive, single-page website built with plain HTML, CSS, and JavaScript, with no frameworks or build tools. It is based on the free **Tooplate 2169 Hustle Bee** template.

**Live demo:** https://jubair211.github.io/jubair-portfolio/2169_hustle_bee/

## Features

- Fully responsive layout (desktop, tablet, mobile)
- Sticky navigation bar that changes style on scroll
- Mobile hamburger menu that closes after selecting a link
- Scroll-reveal animations using the Intersection Observer API
- Active nav link highlighting based on the current section
- Image-based sections and project cards

## Project Structure

    2169_hustle_bee/
    ├── images/                         # All site images
    ├── index.html                      # Main page
    ├── timer.html                      # Timer page (redirects to timermo.com)
    ├── tooplate-2169-hustle-bee.css    # Styles
    └── tooplate-2169-hustle-bee.js     # Nav, scroll reveal, active link logic

## Getting Started

Clone the repository:

    git clone https://github.com/jubair211/jubair-portfolio.git
    cd jubair-portfolio/2169_hustle_bee

Open `index.html` in your browser, or serve it locally:

    python3 -m http.server 8000

Then visit http://localhost:8000.

## Deployment

The site is static, so it works on GitHub Pages:

1. Go to **Settings → Pages**
2. Set the source to `Deploy from a branch`
3. Choose `main` and `/ (root)`, then save

## Customization

- Edit text and sections in `index.html`
- Change colors, fonts, and spacing in `tooplate-2169-hustle-bee.css`
- Replace images in the `images/` folder, keeping the same filenames or updating the paths in `index.html`

## Credits

- Template: [Tooplate 2169 Hustle Bee](https://www.tooplate.com/view/2169-hustle-bee)
- Customized by [Jubair](https://github.com/jubair211)
