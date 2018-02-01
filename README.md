#Header promo

This plugin adds a promo bar above the header.

This can be used to advertise a news article, event, or other important link on the site.

##Dependencies

* jQuery
* Bootstrap

##Getting started

1. Verify that the jQuery and Bootstrap are included in the project.
2. Include *promo.js* in your js directory / gulpfile.
3. Include *_promo.scss* or *promo.css* in your stylesheets. When using SCSS, make sure this file is included in the project after your header SCSS files.
4. Copy the code inside *promo.html* and prepend it to your *.header* container, like so:

```html
<header class="header">
	<div class="promo">
		...
	</div>
	...
</header>
```

Inside the *a* tag, update the href attribute and text to insert your promotion.

Then, re-run gulp, and you're good to go!

