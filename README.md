# Homework. Module 2. HTML & CSS Fundamentals

## Project Requirements

1. Create a repository named `goit-markup-hw-02`.
2. Use repository `goit-markup-hw-01` as a template.
3. Complete the HTML markup for the ["Homework #2"](https://www.figma.com/design/folOvI69KUmwYN47Njpr0O/Web-Studio--Version-5.1-?node-id=296708-626&p=f&t=LgzWYpxJLKTA5yDb-0) page layout without any CSS styling.
4. Set up GitHub Pages and add a link to the live page in the About section of the GitHub repository.
5. In the `goit-markup-hw-02` folder, create the project structure as shown in the diagram below.


## Project Structure

<img width="327" height="787" alt="image" src="https://github.com/user-attachments/assets/bcde2733-761b-4a3d-af90-6e6b0ca42f5b" />



* [x] - The project root contains an `images` directory with all image assets.
* [x] - The project root contains a `css` directory with all stylesheet files.
* [x] - All styles are written in their corresponding CSS files inside the `css` directory and are properly connected.
* [x] - File names do not contain Cyrillic characters or spaces. Only English letters, numbers, and words are used.
* [x] - Source code is formatted using `Prettier`.
* [x] - All images and text content are taken directly from the provided design mockup.
* [x] - The project uses the minified version of ["modern-normalize"](https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/3.0.1/modern-normalize.min.css)
* [x] - The code follows the provided ["coding guidelines"](https://codeguide.co/).

## CSS Organization

1. [x] - Only `main.css` is linked in `index.html`.
2. [x] - `main.css` contains only imports of other stylesheet files and no additional styles.
3. [x] - Stylesheets are imported in the following order:

```css
@import './common.css';
@import './header.css';
@import './hero.css';
@import './features.css';
@import './team.css';
@import './portfolio.css';
@import './footer.css';
```

4. [x] - All `@import` paths must start with `./`.
5. [x] - Global and base styles are defined in `common.css`. Styles specific to individual page sections (header, sections, footer, etc.) are placed in their corresponding CSS files.

---

# Portfolio Section

* [] - The section contains the following ID:

```html
<section id="portfolio">
```

* [x] - The **Our Portfolio** section markup is implemented in `index.html`.
* [x] - All elements from the design mockup are fully marked up in HTML.
* [x] - HTML tags are used according to their semantic meaning.
* [x] - The HTML passes validation without errors.
* [x] - Class names are descriptive and easy for other developers to understand.
* [x] - Class names:

  * Do not contain uppercase letters.
  * Do not contain numbers.
  * Do not contain spaces.
  * Do not use transliteration.
  * Do not contain HTML tag names.
  * Use only English words and letters.
  * Multi-word class names are separated with hyphens (`-`).
* [x] - All `<img>` elements include size attributes, at minimum `width`.
* [x] - Images are exported from the design in `.jpg` format.
* [x] - Groups of similar elements are organized using unordered lists (`<ul>`).
* [x] - All required fonts and font variations (weights and styles) are imported from **Google Fonts** using a single combined link that loads both **Raleway** and **Roboto**.
* [x] - In both the header and footer, the logo uses a `<span>` element to wrap the highlighted `"Web"` portion.

---

# Styling Requirements

* [x] - Class selectors are used for styling.
* [x] - No `!important` declarations are present in the CSS.
* [x] - Interactive elements (buttons and links) have hover and focus states as specified in the Style Guide (color changes).
* [x] - Contact links in the header change color on hover and focus.
* [x] - The `<body>` element defines `font-family` with **Roboto** as the primary font.
* [x] - A generic sans-serif fallback font is included at the end of the `font-family` stack.
* [x] - The `Roboto` font family is explicitly assigned only to the `<body>` element; all other elements inherit it.
* [x] - The `<body>` element defines the primary text color from the design.
* [x] - All text elements use font sizes that exactly match the design specifications.
* [x] - All text elements use line-height values that exactly match the design and are specified as multipliers rather than pixel values.
* [x] - All colors (`color` and `background-color`) exactly match the design.
* [x] - Font weights (`font-weight`) exactly match the design specifications.
* [x] - Font weights are explicitly defined only when they differ from the browser's default value for the element.
* [x] - Buttons use:

```css
cursor: pointer;
```

* [x] - Styles do not duplicate browser default property values. For example:

  * Links should not be assigned `cursor: pointer`.
  * Paragraphs should not explicitly define `font-style: normal` or `font-weight: 400`.

---

# Notes

* [x] - The hidden `<h2>` heading **"Our Features"** should not be styled.
* [x] - For this assignment, the heading should remain visible. Hiding it will be implemented in a future assignment.
