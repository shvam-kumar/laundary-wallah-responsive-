# Laundry Wallah 🧺

A responsive laundry service landing page built with HTML and CSS.

## Project Structure

```
project/
├── index.html
├── style.css
└── README.md
```

## Features

- Responsive navbar with logo, centered navigation links, and username
- Hero section with heading, description, and call-to-action button
- Fully responsive layout using Flexbox
- Tablet and mobile breakpoints

## Responsive Breakpoints

| Breakpoint | Behaviour |
|---|---|
| Desktop (> 768px) | Full navbar + hero side by side |
| Tablet (≤ 768px) | Smaller text/images, hero stacks vertically |
| Mobile (≤ 480px) | Nav links hidden, only logo and username shown |

## Navbar Layout

```
[ Logo ]   [ HOME  Services  About Us  Contact Us ]   [ Laundry Wallah ]
```

- Logo — left
- Nav links — center (flex: 1 + justify-content: center)
- Username — right (margin-left: auto)

## Hero Section

- **Desktop** — text on the left, image on the right (`flex-direction: row`)
- **Tablet/Mobile** — image on top, text below (`flex-direction: column`)

## Technologies Used

- HTML5
- CSS3 (Flexbox, Media Queries)

## How to Run

1. Clone or download the project folder
2. Open `index.html` in any browser

No installations or dependencies required.