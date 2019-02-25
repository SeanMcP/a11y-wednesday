---
title: Label every input!
author:
  name: Sean McPherson
  link: https://twitter.com/_seanmcp
level: beginner
tags: ['input', 'label', 'form']
---

Every form control element should have an associated label. Use the HTML label element whenever possible: 

```html
<!-- Using the for attribute -->
<label for="pw">Password</label>
<input type="password" id="pw">

<!-- Wrapping the input in a label -->
<label>
  <span>Confirm password</span>
  <input type="password" id="pwConfirm">
</label>
```

Alt: A code block with two strategies for labelling input fields: 1) implicitly by wrapping the input element in a label, and 2) explicitly by using HTML's for attribute.

Source: https://www.w3.org/WAI/tutorials/forms/labels/
