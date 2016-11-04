# Techniques for SVG

The purpose of this is to demonstrate various ways that SVGs can be implemented.

While we all love to discuss the various differences between icon delivery as a font vs SVG, it is not the goal of this demonstration.


* Inline `<svg>`
  * Allows for complete styling control
  * Adds bloat to HTML
* External `<img>`
  * Unable to style
  * Leverages cache
* Sprite
  * Symbols vs Def Blocks
  * Def require the `viewBox` to be defined at each instance
  * Allows for complete styling control
* External Reference
  * IE 9 - 11 not supported
  * Leverages cache well
  * Keeps ability to style


### Accessibility
Add `<title>` and `<desc>` tags directly in the `<symbol>` for accessibility


### Helfpul Links
[CSS Tricks - SVG Symbol](https://css-tricks.com/svg-symbol-good-choice-icons/)

[24 Ways - An Overview of SVG Sprite Creation Techniques](https://24ways.org/2014/an-overview-of-svg-sprite-creation-techniques/)

[CSS Tricks - Icon System with SVG Sprites](https://css-tricks.com/svg-sprites-use-better-icon-fonts/)

[CSS Tricks - SVG `use` with External Reference, Take 2](https://css-tricks.com/svg-use-with-external-reference-take-2/)

[GitHub - Delivering Octicons with SVG](https://github.com/blog/2112-delivering-octicons-with-svg<)

[Una - A Gulp-Based External SVG Symbol Sprite Icon System](http://una.im/svg-icons/)


### The Wonderful World of SVG (Video)

[Chris Coyier - The Wonderful World of SVG](https://www.youtube.com/watch?v=tsGa-gcckwY) talk at CSS Conf 2015 is a good overview of SVGs on the web.
