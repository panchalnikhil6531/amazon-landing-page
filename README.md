# Amazon Landing Page

An Amazon-inspired homepage layout built with HTML and CSS as a front-end layout practice project.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)

## Overview

This project recreates the look of the Amazon homepage to practise building a real-world page layout from scratch: a multi-part navigation bar, a full-width hero banner, a grid of product category cards and a multi-column footer. It is a static page made only with HTML and CSS, with no JavaScript, frameworks or build step.

> **Disclaimer:** This is an educational UI practice project. It is not affiliated with, endorsed by, or connected to Amazon.com, Inc. or its affiliates. The Amazon name, logo and imagery belong to their respective owners and are used here for learning purposes only. None of the links or controls are functional.

## Features

- **Navigation bar** – logo, "Deliver to" location block, search bar with category dropdown and search icon, account and "Returns & Orders" sections, and a cart icon, with hover borders on interactive areas.
- **Secondary panel** – "All" menu button, quick links (Amazon Basics, Prime, Today's Deals, Groceries, Customer Service) and a deals banner.
- **Hero section** – full-width background banner with a notice message.
- **Category cards** – two rows of four cards (Clothes, Health & Personal Care, Furniture, Electronics, Beauty Picks, Pet Care, Toys, Fashion Trends), each with a title, image and "See more" link.
- **Footer** – "Back to Top" bar, four columns of links, logo and legal links.
- **Icons** – Font Awesome 6 icons loaded from a CDN.

## Tech Stack

- **HTML5** – semantic page structure
- **CSS3** – Flexbox layouts, background images, hover effects
- **Font Awesome 6.6** (CDN) – icons

## Project Structure

```
amazon-landing-page/
├── index.html        # Page markup
├── style.css         # All styles
├── logo.png          # Logo used in the navbar and footer
├── heroimg.jpg       # Hero banner background
├── box1.jpg … box8.jpg  # Category card images
└── amazon 1.jpg, amazon 2.jpg, logo1.png  # Additional image assets
```

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/panchalnikhil6531/amazon-landing-page.git
   cd amazon-landing-page
   ```

2. Open `index.html` in any modern web browser, or serve the folder locally (for example with the VS Code Live Server extension, or `python -m http.server 8000` and then visit <http://localhost:8000>).

An internet connection is needed for the Font Awesome icons, which load from a CDN.

## What I Practised

- Breaking a complex real-world page into header, hero, content and footer sections
- Building horizontal layouts with Flexbox
- Using background images for banners and cards
- Styling navigation, search inputs and hover states

## Author

**Panchal Nikhil S**

- GitHub: [@panchalnikhil6531](https://github.com/panchalnikhil6531)
- LinkedIn: [Nikhil S Panchal](https://www.linkedin.com/in/nikhil-s-panchal-463a78319/)
- Portfolio: [potfolio-beta-two.vercel.app](https://potfolio-beta-two.vercel.app/)
