---
title: Improve Compatibility with Browser Fallbacks
---
## Improve Compatibility with Browser Fallbacks

To avoid compatibility issues with browsers, it is best to specify properties in case.

Here instead of this code:
```css
.red-box {
background: var(--red-color);
height: 200px;
width:200px;
}
```


It is better to add a solution in case the browser is incompatible with this property:
```css
.red-box {
background: red; /* Add this Add this property. */
background: var(--red-color);
height: 200px;
width:200px;
}
```
