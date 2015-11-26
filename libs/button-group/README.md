<p class="u-text-emphasize">This library provides a base to group buttons together on a single line.</p>

This library works great with the `button` library but can work without.

```html
<div class="c-button-group">
	<a class="c-button-group__item c-button" href="Button">Button</a>
	<a class="c-button-group__item c-button" href="Button">Button</a>
	<a class="c-button-group__item c-button" href="Button">Button</a>
</div>  
```

### .c-button-group--rounded

Rounds edges of the first and last button.

```html
<div class="c-button-group c-button-group--rounded">
	<a class="c-button-group__item c-button" href="Button">Button</a>
	<a class="c-button-group__item c-button" href="Button">Button</a>
	<a class="c-button-group__item c-button" href="Button">Button</a>
</div>
```

### .c-button-group--border

Removes double borders when buttons have borders.

`Note: Only works for 1px borders`

```html
<div class="c-button-group c-button-group--border">
	<a class="c-button-group__item c-button" href="Button">Button</a>
	<a class="c-button-group__item c-button" href="Button">Button</a>
	<a class="c-button-group__item c-button" href="Button">Button</a>
</div>
```

### Spacing

##### .c-button-group--gutter-[small|large]

Adds spacing between buttons.

```html
<div class="c-button-group c-button-group--gutter-small">
	<a class="c-button-group__item c-button" href="Button">Button</a>
	<a class="c-button-group__item c-button" href="Button">Button</a>
	<a class="c-button-group__item c-button" href="Button">Button</a>
</div>
```