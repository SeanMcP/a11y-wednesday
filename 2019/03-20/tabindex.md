---
title: tabindex
author:
  name: Sean McPherson
  link: https://twitter.com/_seanmcp
level: Beginner
tags: [tabindex, keyboard navigation]
---

Use the html attribute tabindex to enable or disable keyboard focus on elements. Pass "0" to enable focus or "-1" to disable it.

You don't need to pass a value greater than "0".

```html
<!-- Disable keyboard focus with "-1" -->
<button tabindex="-1" type="reset">Reset</button>

<!-- Enable keyboard focus with "0" -->
<li tabindex="0" role="option"> ... </li>
```

Alt: An html code block demonstrating how to disable keyboard focus with tabindex="-1" and enable it with tabindex="0".

Source: https://webaim.org/techniques/keyboard/tabindex
