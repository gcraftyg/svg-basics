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


[CSS Tricks SVG Symbol](https://css-tricks.com/svg-symbol-good-choice-icons/)



#### Things to cover
1. Markup
2. Styling / Adjusting Colors
3. Animation
4. Browser Support
