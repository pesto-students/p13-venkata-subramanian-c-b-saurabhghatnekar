# CSS Fundamentals

- CSS stands for Cascading Style Sheets.
- CSS is a language used to style HTML elements.
- CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

### CSS Syntax

- CSS is a rule-based language. You define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page.
- A CSS rule consists of a selector and a declaration block:
  - The selector
  - The declaration block
  - The declaration
  - The property
  - The value
  - The declaration block is enclosed in curly braces.

### CSS Selectors

- CSS selectors are used to "find" (or select) the HTML elements you want to style.
- CSS selectors select HTML elements according to its id, class, type, attribute, etc.

### CSS Units

- CSS has several different units for expressing a length.
- Many CSS properties take "length" values, such as width, margin, padding, font-size, etc.
- Absolute length units are fixed and a length expressed in any of these will appear as exactly that size.
- Relative length units specify a length relative to another length property.
- The relative length units are:
  - em
  - ex
  - ch
  - rem
  - vw
  - vh
  - vmin
  - vmax
  - %
- The em and rem units are practical in creating perfectly scalable layout!
- The em unit is relative to the font-size of the parent, which causes the compounding issue.
- The rem unit is relative to the root—or the html—element. That means that we can define a single font size on the html element and define all rem units to be a percentage of that.

### CSS Colors

- Colors in CSS can be specified by the following methods:
  - Hexadecimal colors
  - RGB colors
  - RGBA colors
  - HSL colors
  - HSLA colors
  - Predefined/Cross-browser color names
  - Opacity

### CSS Backgrounds

- The CSS background properties are used to add background effects for elements.
- The CSS background properties are:
  - background-color
  - background-image
  - background-repeat
  - background-attachment
  - background-position

### CSS Borders

- The CSS border properties allow you to specify the style, width, and color of an element's border.
- The CSS border properties are:
  - border-style
  - border-width
  - border-color
  - border-top
  - border-right
  - border-bottom
  - border-left
  - border-radius

### CSS Margins

- The CSS margin properties are used to create space around elements, outside of any defined borders.
- The CSS margin properties are:
  - margin
  - margin-top
  - margin-right
  - margin-bottom
  - margin-left

### CSS Padding

- The CSS padding properties are used to generate space around an element's content, inside of any defined borders.
- The CSS padding properties are:
  - padding
  - padding-top
  - padding-right
  - padding-bottom
  