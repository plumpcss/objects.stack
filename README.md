# The stack object

The stack object simply layers media and/or text-like content on top of each other.

The element that stack is applied to either needs defined height and width or a non-layer element within it to control its width and height. Without either, every element would be absolutely positioned so the container will collapse to 0x0.

```html
	<div class="stack">
		<img src="//placekitten.com/500/400" alt="Kitten" />
		<div class="stack__layer">
			<p>This is a default placeholder image provided by placekitten.</p>
		</div>
	</div>
```
