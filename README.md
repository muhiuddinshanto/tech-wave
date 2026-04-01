# TechWave Podcast Landing Page

## Overview

TechWave is a modern and fully responsive podcast landing page built with only HTML and CSS. The website is designed for a fictional tech podcast brand called “TechWave”. It highlights podcast episodes, host information, podcast statistics, and listening platforms with a clean dark-themed UI.

The project focuses on attractive layout design, responsive structure, smooth spacing, gradient styling, and organized content sections.

---

## Live Features

* Responsive navigation for desktop and mobile
* Hero section with animated microphone image
* Podcast introduction and statistics section
* “Why Choose TechWave” feature grid
* Featured podcast episode cards
* Meet the host section with social icons
* Fully responsive footer with platform links
* Gradient buttons and text effects

---

## Technologies Used

* HTML5
* CSS3
* Flexbox
* CSS Grid
* Media Queries
* Font Awesome
* Google Fonts

---

## Why These Technologies Were Used

### HTML5

Used to create the complete structure of the website including navigation, banner, podcast cards, host section, and footer.

### CSS3

Used for all styling, including:

* Colors
* Layout spacing
* Typography
* Background images
* Hover effects
* Border radius
* Gradients

### Flexbox

Used in places where items needed to stay in a row and align easily.

Examples:

* Navigation bar
* Banner buttons
* Footer icons
* Host social icons

### CSS Grid

Used for the “Why Choose TechWave” section to create a modern multi-column card layout.

### Media Queries

Used to make the website fully responsive for:

* Mobile devices
* Tablets
* Large screens

---

## Main Sections of the Website

### 1. Navigation Bar

The website contains two separate navigation layouts:

* Desktop navigation
* Mobile navigation with hamburger icon

Desktop menu includes:

* About
* Episodes
* Host
* Subscribe button

---

### 2. Hero / Banner Section

The banner section includes:

* Background image
* Circular hero graphic
* Floating microphone animation
* Podcast title
* Description text
* Two call-to-action buttons:

  * Listen on Spotify
  * Subscribe

The microphone image uses CSS animation to create a floating effect.

---

### 3. About Podcast Section

This section explains what the podcast is about and includes statistics such as:

* 150K+ Monthly Listeners
* 200+ Episodes Published
* 4.9★ Average Rating
* 50+ Industry Experts

---

### 4. Why Choose TechWave Section

This section uses CSS Grid to display podcast advantages.

Cards include:

* Premium Audio Quality
* Mobile Friendly
* Global Community
* Exclusive Interviews
* Rich Resources

---

### 5. Featured Episodes Section

This section displays three podcast episode cards.

Each card contains:

* Thumbnail image
* Play icon
* Episode title
* Description
* Duration

---

### 6. Meet the Host Section

This section introduces the podcast host.

It contains:

* Host image
* Host name
* Biography
* Social media icons

---

### 7. Footer

The footer contains:

* Brand logo
* Listening platform links
* Copyright text

Platforms shown:

* Spotify
* Apple Podcasts
* YouTube
* Twitter

---

## Folder Structure

```text
TechWave/
│
├── index.html
├── style.css
├── responsive.css
└── images/
    ├── hero-bg.png
    ├── hero-circle.png
    ├── microphone.png
    ├── host.png
    ├── thamb-1.jpg
    ├── thamb-2.jpg
    ├── thamb-3.jpg
    └── more images...
```

---

## Responsive Design

The website supports 3 different screen sizes:

| Device  | Width         |
| ------- | ------------- |
| Mobile  | Below 576px   |
| Tablet  | 576px – 992px |
| Desktop | Above 992px   |

Responsive changes include:

* Smaller text sizes
* Grid becomes single-column
* Cards stack vertically
* Navigation switches to mobile version
* Footer items wrap automatically

---

## Special Design Features

* Custom CSS variables for colors
* Gradient text and buttons
* Animated floating microphone
* Rounded card design
* Dark modern theme
* Fully reusable utility classes like:

  * `.flex`
  * `.width`
  * `.btn`

---

## Future Improvements

Possible improvements for the project:

* Add JavaScript for interactive mobile menu
* Add dark/light theme toggle
* Add slider for featured episodes
* Connect subscribe button with email form
* Add podcast audio player
* Add smooth scrolling navigation

---

## Live Demo

You can view the live project here:

* [https://muhiuddinshanto.github.io/tech-wave/]


