# Nutrition Label Ass-3 CSS

## Hosted Link : https://saifulislam05.github.io/nutrition-lebel

## Project Description
The Nutrition Label CSS project showcases a styled nutrition label typically found on food packaging. It uses HTML and CSS to create an informative and visually appealing nutrition facts display.

## HTML Structure
- `<h1>`: Represents the project title.
- `.label`: Wraps the entire nutrition label.
- `<header>`: Contains the label header information.
- `<p>`: Displays various text content within the header.
- `.divider`: Creates horizontal dividers for section separation.
- `.calories-info`: Displays calorie information.
- `.left-container` and `span`: Represent calorie amount per serving.
- `.daily-value`: Displays daily value percentages.
- `.note`: Provides a note regarding daily values.

## CSS Styles

### Global Styles
- `*`: Sets box-sizing to border-box and standardizes font size.
- `html`: Sets the base font size for responsive design.
- `body`: Applies a specified font-family to the entire page.

### `.label` Selector:
- `border`: Adds a border around the label.
- `width`: Sets the label's width.
- `margin`: Centers the label horizontally with margin.
- `padding`: Adds padding to the label's content.

### `header h1` Selector:
- `text-align`: Centers the project title text.
- `margin`: Adjusts the margin for precise alignment.
- `letter-spacing`: Adds letter spacing for visual appeal.

### `.divider` Selector:
- `border-bottom`: Creates horizontal dividers.
- `margin`: Adjusts the margin for proper spacing.

### `.bold` Selector:
- `font-weight`: Sets text to bold (800).

### `.large`, `.medium` Selectors:
- `height`: Adjusts the height of dividers.
- `background-color`: Sets background color for dividers.

### `.small-text` Selector:
- `font-size`: Reduces font size for small text.

### `.calories-info` Selector:
- `display`: Uses flex layout for content alignment.
- `justify-content`: Aligns content within the flex container.
- `align-items`: Aligns items vertically within the container.

### `.calories-info h2` Selector:
- `margin`: Adjusts the margin for precise alignment.

### `.left-container p` and `.calories-info span` Selectors:
- `margin`: Adjusts margins for layout and alignment.
- `font-size`: Sets font size for textual content.
- `font-weight`: Sets text to bold (700).

### `.right` Selector:
- `justify-content`: Aligns content to the right.

### `.indent` and `.double-indent` Selectors:
- `margin-left`: Indents text for visual hierarchy.

### `.daily-value p:not(.no-divider)` Selector:
- `border-bottom`: Adds a bottom border to specific paragraphs.

### `.note` Selector:
- `font-size`: Sets font size for the note.
- `margin`: Adds margin for spacing.
- `padding`: Adjusts the padding for a clean look.
- `text-indent`: Indents text for readability.
