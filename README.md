# Blinkit Homepage Clone

A responsive clone of the [Blinkit](https://blinkit.com/) homepage built with **HTML5** and **CSS3** only. No JavaScript and no frameworks. It was made as a frontend assignment and works on desktop, tablet and mobile screens.

> This project is for learning purposes only. It is not affiliated with Blinkit. All brand names belong to their respective owners.

## Features

- Sticky header with logo, delivery time and address, search bar, Login link and My Cart button
- Green hero banner with heading, description, "Shop Now" button and image
- Three promo cards (Pharmacy, Pet Care, Baby Care) with hover lift effect
- Category grid with 20 grocery categories, each with an image and a name
- Fully responsive layout using Flexbox and CSS Grid
- No horizontal scrolling on any screen size
- Semantic HTML (`header`, `nav`, `main`, `section`, `article`, `footer`) with alt text on all images

## Tech Stack

- HTML5
- CSS3 (Flexbox, Grid, media queries, CSS variables)
- Google Fonts (Inter)

## Responsive Breakpoints

| Screen | Width | Category grid | Promo cards |
|---|---|---|---|
| Mobile | below 480px | 3 columns | 1 column |
| Large mobile | 480px and above | 4 columns | 1 column |
| Tablet | 768px and above | 6 columns | 3 columns |
| Desktop | 1024px and above | 10 columns | 3 columns |

On very small screens the delivery info is hidden and the search bar moves below the logo row, so everything fits without overlapping.

## Project Structure

```
blinkit-clone/
├── index.html
├── style.css
├── README.md
└── Assets/
    └── images/
        ├── banner-fruits.svg
        ├── pharmacy.svg
        ├── pet-care.svg
        ├── baby-care.svg
        └── 20 category images (paan, dairy, fruits-veg, cold-drinks,
            snacks, breakfast, sweet, bakery, tea-coffee, atta-rice,
            masala, sauces, meat, organic, baby, pharma, cleaning,
            home-office, personal-care, pet)
```

## How to Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open the folder in VS Code
3. Right-click `index.html` and choose **Open with Live Server**, or double-click `index.html` to open it in your browser

## How to Test Responsiveness

1. Open the page in Chrome
2. Press `F12` and click the device toolbar icon
3. Check these widths: **375px** (mobile), **768px** (tablet), **1280px** (desktop)

## Deploy on GitHub Pages

1. Push the project to a GitHub repository
2. Go to **Settings > Pages**
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**
4. Your site will be live at `https://your-username.github.io/your-repo-name/`

> GitHub Pages is case-sensitive. The folder name in the code is `Assets/images/`, so the folder must be named exactly `Assets` with a capital A.

## What I Learned

- Building layouts with Flexbox and CSS Grid
- Making a mobile-first responsive design with media queries
- Structuring clean, semantic HTML and organized CSS with variables
- Matching the look of a real website without copying it pixel for pixel

## Author
Tushar Rajput
