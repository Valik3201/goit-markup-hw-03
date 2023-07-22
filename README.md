# Web Studio Project - HTML, CSS, and Flexbox Styling

Welcome to the Web Studio project continuation! In this part of the project, the focus has been on enhancing the graphic design and layout of web pages using CSS styles and the Flexbox positioning technique.

## Project Contents

### HTML Markup

- The project includes HTML files that form the structure of the web pages, including `index.html`, `portfolio.html`, and any other necessary HTML files.
- Each page is marked up with appropriate HTML tags, following semantic guidelines and the provided tutorials.
- All images and textual content are carefully placed within the layout, ensuring they are correctly structured.

### CSS Styling and Flexbox

- All styles for the project are consolidated in a single CSS file named `styles.css`, located in the `css` folder.
- The CSS file contains styles for geometry, such as widths, padding, margins, and borders, to ensure precise positioning and alignment of elements.
- The Flexbox positioning technique is utilized, especially in the header, navigation, lists within sections, and other areas where horizontal layout is required.
- The CSS code is formatted using Prettier, maintaining code consistency and readability.

### Normalization

- All HTML pages in the project have been equipped with the modern-normalize stylesheet. This ensures consistent rendering across different browsers, reducing cross-browser inconsistencies.

## Styling Guidelines

### Global Reset

- It is permitted to apply a global reset of styles for `<h1>...<h6>`, `<p>`, and `<ul>` elements, ensuring consistent and uniform styling.

### Margins and Padding

- Elements do not have outer margins (using the `margin` property) that "collapse" and interfere with their parent elements.
- In collections of elements in a single row, the left or right margins of extreme elements are removed, if present.
- The `margin` property is used when defining margins between adjacent elements.
- The `padding` property is used to set the spacing between a parent element and its child elements.

### Container Class

- A general utility class `.container` is created to center and constrain the width of content.
- The width of `.container` adheres to the layout requirements and is set to 1158px.
- `.container` wraps the content of the header, footer, and sections, indicating that it is inside them.

### Flexbox Layout

- Flexbox is used to position elements horizontally when needed, such as in the header, navigation, and lists within sections.
- Final block sizes in the browser match the layout, providing a consistent appearance.

### Flexible Heights

- Elements do not have fixed heights; their height depends on their content.

### Borders

- The header has a bottom border, which becomes visible when enlarged.

### Section Styling

- Sections are stacked on top of each other like a stack of books, without external margins.
- A common class `.section` is used for all sections, with top and bottom padding set to 120px, providing internal spacing for content.

### Grid Building

- The layout's grid system is constructed using the technique described in the tutorial.

### Card Borders

- Cards on the Portfolio page have borders (`border` property), but only at the bottom of the card.

## Conclusion

This part of the Web Studio project focuses on implementing the CSS styles, including geometry, positioning, and layout using Flexbox.
