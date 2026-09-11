# Task 3: CSS Units, Box Models, Fonts

## Description
This project demonstrates layout structuring using viewport units (`vw`, `vh`) and the CSS Box Model, strictly adhering to the constraints of avoiding Flexbox, CSS positioning (`absolute`, `relative`), and `overflow: hidden`. The layout ensures the page perfectly fits the viewport without scrolling.

## Files Included
* `index.html`: Contains the structural markup for the image and button.
* `style.css`: Contains the styling rules ensuring proper spacing (25% lateral, 10% vertical margins), gradient button styling, and viewport-based sizing.
* `README.md`: Project documentation.

## Key Concepts Demonstrated
* **Viewport Units:** Utilizing `vw` and `vh` to calculate widths, heights, and margins dynamically based on the screen size (e.g., `25vw` left/right margins, `10vh` top/bottom margins).
* **Box Sizing:** Applying `box-sizing: border-box` universally to ensure borders and padding do not increase the computed size of elements.
* **Scroll Prevention:** Carefully calculating dimensions (e.g., `margin-top` + `height` + `margin-bottom` = `100vh`) to prevent horizontal and vertical scrolling without relying on `overflow: hidden`.
* **Gradients & Fonts:** Styling the button with a linear gradient and viewport-responsive font sizing.

## How to Run
1. Ensure both `index.html` and `style.css` are in the same directory.
2. Open `index.html` in any modern web browser to view the rendered webpage.
3. Resize the browser window to observe how the elements scale dynamically with the viewport without triggering scrollbars.