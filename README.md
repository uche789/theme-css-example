# Theme CSS example
An example of multiple theme support using CSS variables.

[DEMO](https://uche789.github.io/projects/theme-css-example/)

## Solution
Global CSS variables are usually defined in the `:root` selector. Because of legacy browser support, you should define all css variables here.

**Default variables:**
```css
:root {
    --font-family: Georgia, Cambria, san-serif;
    --text-color: #000;
}
```

**Default variables:**
```css
:root {
    --font-family: 'Open Sans', sans-serif;
    --text-color: #666;
}
```

Add the theme variables to the page below the default variables. Et voilà!

## Support for IE and legacy browser
[css-vars-ponyfill](https://github.com/jhildenbiddle/css-vars-ponyfill) provides support for legacy browsers and it's implementation is pretty straight-forward.