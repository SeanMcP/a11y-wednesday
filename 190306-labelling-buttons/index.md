---
title: Labelling buttons
author:
  name: Sean McPherson
  link: https://twitter.com/_seanmcp
level: Beginner
tags: [buttons, label]
---

A button's action should be indicated by content of the element. For image or icon buttons, use an alt tag on the child or aria-label on the button.

```html
<button>Send message</button>

<button>
  <img src="paper-plane.svg" alt="Send message">
</button>

<button aria-label="Send message">
  <i class="fas fa-paper-plane"></i>
</button>
```

Alt: A code block demonstrating three ways to correctly label buttons: 1) an internal string, 2) an image with an alt tag, and 3) an icon with an aria-label on the button.

Source: https://www.w3.org/WAI/tutorials/forms/labels/#labelling-buttons
