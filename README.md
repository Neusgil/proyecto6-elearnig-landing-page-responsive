# Skilled E-learning Landing Page

Responsive landing page developed from a Figma design as part of my frontend development practice.

The project follows a **mobile-first approach** and reproduces the supplied designs for mobile, tablet and desktop, including responsive layouts and interactive hover states.

## Features

- Responsive design
- Mobile-first workflow
- Mobile, tablet and desktop layouts
- Interactive hover states
- Responsive hero section
- Course cards layout
- Informational statistics cards
- Gradient buttons and backgrounds
- SCSS architecture organized by components
- Figma-based implementation

## Built with

- HTML5
- SCSS / Sass
- CSS Grid
- Flexbox
- BEM methodology
- Vite

## Responsive breakpoints

```scss
$breakpoint-tablet: 768px;
$breakpoint-desktop: 1200px;
```

The base styles correspond to the mobile version.

## Project structure

```text
proyecto6-elearnig-landing-page-responsive/
│
├── public/
│   └── img/
│
├── src/
│   ├── assets/
│   └── main.js
│
├── scss/
│   ├── base/
│   │   ├── _reset.scss
│   │   └── _typography.scss
│   │
│   ├── components/
│   │   ├── _buttons.scss
│   │   └── _cards.scss
│   │
│   ├── layout/
│   │   ├── _footer.scss
│   │   ├── _header.scss
│   │   └── _hero.scss
│   │
│   ├── utils/
│   │   ├── _mixins.scss
│   │   └── _variables.scss
│   │
│   └── style.scss
│
├── index.html
├── package.json
└── README.md
```

## Interactive states

The desktop version includes hover states based on the Figma design:

- Header button changes color on hover
- Hero CTA changes appearance on hover
- Footer CTA changes appearance on hover
- Course links change to a lighter pink
- Statistics cards appear when hovering over the hero image

## What I practiced

This project helped me practice:

- Translating a Figma design into code
- Building responsive layouts
- Working with exact dimensions and spacing
- Organizing SCSS into partials
- Using variables and mixins
- Managing responsive breakpoints
- Working with absolute positioning
- Using pseudo-elements
- Creating hover interactions
- Building a project with Vite and Sass

## Author

**María Nieves**

GitHub: **Neusgil**
