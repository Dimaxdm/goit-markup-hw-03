# Homework. Module 3. Box Model & Flexbox

## Project Requirements

1. Create a repository named `goit-markup-hw-03` (you may use the provided Template repository).
2. Clone the repository and copy the files from the previous homework if you did not create it from the Template.
3. Add CSS for layout geometry (widths, margins, padding, borders) and position page content using **Flexbox** according to the ["Homework #2"](https://www.figma.com/design/folOvI69KUmwYN47Njpr0O/Web-Studio--Version-5.1-?node-id=296708-626&p=f&t=LgzWYpxJLKTA5yDb-0) design.
4. Set up GitHub Pages and add the link to the live page in the **About** section of the GitHub repository.


* [x] - The project root contains an `images` directory with all image assets.
* [x] - The project root contains a `css` directory with all stylesheet files.
* [x] - All styles are written in their corresponding CSS files inside the `css` directory and are properly connected.
* [x] - File names do not contain Cyrillic characters or spaces. Only English letters, numbers, and words are used.
* [x] - Source code is formatted using `Prettier`.
* [x] - All images and text content are taken directly from the provided design mockup.
* [x] - The project uses the minified version of [`modern-normalize`](https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/3.0.1/modern-normalize.min.css).
* [x] - The code follows the provided [coding guidelines](https://codeguide.co/).

---

## Project Structure

<img width="327" height="787" alt="image" src="https://github.com/user-attachments/assets/bcde2733-761b-4a3d-af90-6e6b0ca42f5b" />

---

## Layout & Styling Requirements

* [x] - Global CSS resets for `<h1>`–`<h6>`, `<p>`, and `<ul>` are allowed.
* [x] - Do not use shadows or other decorative effects. Focus only on layout geometry and positioning.
* [x] - Elements must not have margins that collapse outside their parent containers.
* [x] - Vertical spacing between adjacent elements is created using the `margin` property.
* [x] - Space between a parent element and its children is created using the `padding` property.
* [x] - All `margin` and `padding` values match the design specifications exactly.
* [x] - A reusable `.container` utility class is created to center content and constrain its width.
* [x] - The `.container` width is **1158px**, matching the design.
* [x] - The `.container` wraps the content of the header, footer, and all page sections.
* [x] - **Flexbox** is used only where appropriate (e.g., header, navigation, lists, cards, and other horizontal layouts).
* [x] - The final block dimensions in the browser match the design.
* [x] - Elements do not have fixed heights unless explicitly required; their height is determined by their content.
* [x] - The header height is defined by its content and the vertical padding of its links.
* [x] - The header includes a subtle bottom border, matching the design.
* [x] - Navigation links in the header have heights determined by their content and vertical padding.
* [x] - Sections are stacked vertically without external margins between them.
* [x] - All sections use a shared `.section` class with `padding: 120px 0`.
* [x] - The hidden heading in the second section uses the following `sr-only` utility class in `common.css`:

```css
.sr-only {
  position: absolute;
  white-space: nowrap;
  width: 1px;
  height: 1px;
  overflow: hidden;
  border: 0;
  padding: 0;
  clip: rect(0 0 0 0);
  clip-path: inset(100%);
  margin: -1px;
}
```

* [x] - Cards in the **Our Portfolio** section have a border only around the bottom content area.



