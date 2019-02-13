---
title: Safely hide elements with a helper class
author:
  name: Sean McPherson
  link: https://twitter.com/_seanmcp
level: intermediate
tags: ['hide', 'element', 'safely']
---

To hide an HTML element from view while keeping it accessible to screen readers, position it far off screen with a helper class. Make sure you're still managing and displaying a focus state!

```css
/* Use with caution */

.--visually-hidden {
  position:absolute;
  left:-10000px;
  top:auto;
  width:1px;
  height:1px;
  overflow:hidden;
}
```
Alt: A code block of CSS styles to safely hide an element from view while keeping it accessible for screen readers

Source: https://webaim.org/techniques/css/invisiblecontent/
