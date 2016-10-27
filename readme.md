# Techniques for SVG

The purpose of this is to demonstrate various ways that SVGs can be implemented.

While we all love to discuss the various differences between icon delivery as a font vs SVG, it is not the goal of this demonstration.



## Inline

```
<img src="" />

```

## External (as img)


## External SVG loading
Does not support IE 9 - 11


## SVG Sprite
### Def Blocks
Require the aspect ratio be applied at the `<use>` tag

```

```


### Symbols
Define aspect ratio on the `<symbol>` and reference the symbol's `id` with the `<use>` tag

```

```

Add `<title>` and `<desc>` tags directly in the `<symbol>` for accessibility

```

```
[CSS Tricks SVG Symbol](https://css-tricks.com/svg-symbol-good-choice-icons/)



#### Things to cover
1. Markup
2. Styling / Adjusting Colors
3. Animation
4. Browser Support
