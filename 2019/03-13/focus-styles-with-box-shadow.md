---
title: Focus styles with box-shadow
author:
  name: Sean McPherson
  link: https://twitter.com/_seanmcp
level: beginner
tags: ['css', 'focus', 'box-shadow', 'outline']
---

Focus styles help your users navigate your web app with a keyboard. If you need to change the default focus styles, replace it with an accessible alternative like box-shadow.

```css
/*
  Only remove the default focus styles if
  you have a plan for replacing them
*/

*:focus {
  outline: none;
  box-shadow: 0 0 2px 2px dodgerblue;
}
```

Alt: A code block illustrating the CSS to remove the default focus styles and replace them with box-shadow. Two inset images show a "before and after" comparison between the default and adjusted styles.

Source: https://dev.to/hybrid_alex/better-css-outlines-with-box-shadows-1k7j
