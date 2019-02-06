---
title: Add help text to forms with aria-describedby
author:
  name: Sean McPherson
  link: https://twitter.com/_seanmcp
level: intermediate
tags: ['forms', 'help', 'aria', 'aria-describedby']
---

Add help text to form elements using `aria-describedby`. Make sure to add `tabindex="-1"` for Internet Explorer support.

```html
<label for="pw-input">Select a new password:</label>
<input id="pw-input" name="pw" type="password" aria-describedby="pw-help" />
<p id="pw-help" tabindex="-1">At least 8 characters with one number</p>
```

Alt: A code snippet with a label, input, and help text demonstrating `aria-describedby`.

Source: https://www.w3.org/WAI/tutorials/forms/instructions/#using-aria-describedby
