---
title: Lang attribute
author:
  name: Sean McPherson
  link: https://twitter.com/_seanmcp
level: beginner
tags: ['html', 'lang', 'attribute', 'screen reader']
---

¿Cual idioma? Set the lang attribute on the html tag of your document to let a screen reader know which language to use. If there is content on the page in a different language, add another lang attribute to that element.

```html
<!DOCTYPE html>

<!-- Set the page's default language on the html tag -->
<html lang="en">
    <body>
		<main>
    		<p>This paragraph will be read in English</p>
          	<!-- Override the default on any element -->
    		<p lang="es">Este párrafo será leído en español.</p>
    	</main>
	</body>
</html>
```

Alt: An HTML code block demonstrating adding a default language with the lang attribute on the html element, then overriding it with a specific child element.

Source: https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang
