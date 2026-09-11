# CSS Selectors Task

## Description
This project is a practical assignment demonstrating the use of various CSS selectors, including class selectors, ID selectors, element selectors, and structural pseudo-classes (`nth-child`, `nth-of-type`). The goal is to match a specific expected visual output strictly using external CSS, avoiding inline styles or adding unnecessary classes/IDs to certain elements.

## Files Included
* `index.html`: Contains the structural markup for the headings, paragraphs, and lists.
* `style.css`: Contains all the styling rules applied to the HTML elements to match the expected output.
* `README.md`: Project documentation.

## Key Concepts Demonstrated
* **Element Selectors:** Styling all `<p>` tags universally.
* **Class Selectors:** Applying styles to multiple headings using `.head`.
* **ID Selectors:** Targeting specific elements like `#bglime` and `#para` for unique styling.
* **Descendant Selectors:** Styling `<span>` within `#bglime` or `<a>` tags within `<li>`.
* **Pseudo-classes (`:nth-child`, `:nth-of-type`):** Used to style specific list items and anchor tags uniquely without adding extra classes or IDs to the HTML markup (fulfilling the specific task constraint: "Show this output without inline CSS nor using class or id for 'a' tag").

## How to Run
1. Download or extract the project folder containing the files.
2. Ensure both `index.html` and `style.css` are in the same directory.
3. Double-click `index.html` or open it in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered webpage.