## Video Answer Notes

These are short, natural answers you can read and slightly personalize in your own voice.

### 1. What is the difference between a `<div>` and a `<span>`? When would you use each?

`<div>` is a block-level element, so it usually starts on a new line and is used to group bigger sections or layout parts of a page.  
`<span>` is an inline element, so it stays inside a line of text and is used for styling or targeting a small part of text or content.

I would use a `<div>` for things like a card, section, or container. I would use a `<span>` when I want to highlight a word, style part of a heading, or target a small inline piece of content.

### 2. What is the CSS Box Model? Explain `content`, `padding`, `border`, and `margin`.

The CSS Box Model is the way every HTML element is treated like a box on the page.

- `content` is the actual text, image, or inner material inside the element.
- `padding` is the space between the content and the border.
- `border` is the visible line around the padding and content.
- `margin` is the outer space between the element and other elements.

So from inside to outside, it goes: content, padding, border, and margin.

### 3. What is the difference between a CSS `class` and an `id`? When should you use one over the other?

A `class` is reusable. You can give the same class to many elements.  
An `id` is unique and should only be used once on a page.

I use a `class` for styling repeated items like buttons, cards, or sections. I use an `id` when I need a unique target, like a section link for navigation or one specific element on the page.

### 4. What is Flexbox, and what's the difference between `justify-content` and `align-items`?

Flexbox is a CSS layout system that helps arrange items in a row or column and makes alignment much easier.

- `justify-content` controls alignment along the main axis.
- `align-items` controls alignment along the cross axis.

If the flex direction is row, `justify-content` works horizontally and `align-items` works vertically. If the flex direction is column, that behavior changes with the axis.

### 5. What is the difference between `position: relative`, `absolute`, and `fixed` in CSS?

`position: relative` means the element stays in the normal document flow, but you can move it slightly using top, left, right, or bottom.

`position: absolute` means the element is removed from the normal flow and positioned relative to its nearest positioned ancestor.

`position: fixed` means the element is removed from the normal flow and stays fixed relative to the browser window, even when the page scrolls.

A common example is using `relative` on a card, `absolute` on a badge inside that card, and `fixed` for something like a floating help button.
