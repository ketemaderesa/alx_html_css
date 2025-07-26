CSS Basic Project

This project is part of the **ALX Frontend Foundations** curriculum.  
The goal is to build a simple static website using **only HTML, CSS, and JavaScript** (no external frameworks or libraries).  
All code is W3C-compliant and validated using the [W3C Validator](https://validator.w3.org/).

---

## Requirements

- All files must end with a new line.
- A `README.md` file is mandatory at the root of the project.
- **No external libraries** (no NodeJS, React, VueJS, Bootstrap, etc.).
- Use only **HTML**, **CSS**, and **JavaScript**.
- Code must be **W3C compliant**.
- Follow proper directory structure and file naming conventions.

---

## Project Structure

alx_html_css/
├── css_basic/
│ ├── base.css
│ ├── styles.css
│ ├── index.html
│ ├── tweets.html
└── README.md
---

## Tasks

### 0. Some Early Styling
- Copy `index.html` and `tweets.html` from `html_basic` directory.
- Create `styles.css` (empty).
- Create `base.css` (provided starter styles).
- Link the CSS files inside `<head>`:
  ```html
  <link href="base.css" rel="stylesheet">
  <link href="styles.css" rel="stylesheet">
Result: Pages now have improved default styling.

1. Positioning (Flexbox)
Convert layout using Flexbox:

<body> uses display: flex; flex-direction: column;

<main> uses display: flex; flex-direction: row;

<main> has flex: auto;

<article> uses flex: 2; overflow-y: auto;

<aside> uses flex: 1; overflow-y: auto;

Result:

+---------------------+
|      <header>       |
+---------------------+
| <article> | <aside> |
+---------------------+
|      <footer>       |
+---------------------+
2. Responsive Web Design
Add class="works_on_smartphone" to <body>.

Add viewport meta tag in <head>:

<meta name="viewport" content="width=device-width, initial-scale=1.0">
Result: Layout adjusts for mobile devices and smaller screens.

3. More Styling
Customize website appearance:

Add colors, borders, backgrounds, and fonts in styles.css.

Add a logo to the <header> using Unicode characters and class="logo".

Modify content and style inside <article> freely.

Restriction: Do not modify Flexbox layout strategy.

Validation
Validate HTML and CSS using W3C Validator.

Repository
GitHub repository: alx_html_css

Directory: css_basic

Files:

base.css

styles.css

index.html

tweets.html

Author
Ketema Deresa
ALX Software Engineering Program

---