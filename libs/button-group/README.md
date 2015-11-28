<p class="u-text-emphasize">This library provides a structural base for grouping buttons together on a single line.</p>

```html
<div class="c-button-group">
	<a class="c-button-group__item c-button" href="Button">Hold</a>
	<a class="c-button-group__item c-button" href="Button">Me</a>
	<a class="c-button-group__item c-button" href="Button">Tight</a>
</div>  
```

## Types

`.c-button-group--round` rounds of the first and last button giving a toolbar style look.

```html
<div class="c-button-group c-button-group--round">
	<a class="c-button-group__item c-button" href="Button">Hold</a>
	<a class="c-button-group__item c-button" href="Button">Me</a>
	<a class="c-button-group__item c-button" href="Button">Tight</a>
</div>
```

Use `.c-button-group--border` to fix the double border problem when buttons have borders.

*Note: This only work when buttons have 1px border.*

```html
<div class="c-button-group c-button-group--border">
	<a class="c-button-group__item c-button" href="Button">Hold</a>
	<a class="c-button-group__item c-button" href="Button">Me</a>
	<a class="c-button-group__item c-button" href="Button">Tight</a>
</div>
```

## Spacing

To give the buttons gutter spacing, use `.c-button-group--gutter-tiny`, `.c-button-group--gutter-small`, `.c-button-group--gutter`, `.c-button-group--gutter-large` or `.c-button-group--gutter-huge`.

```html
<div class="c-button-group c-button-group--gutter-tiny u-margin-bottom">
	<a class="c-button-group__item c-button" href="Button">Don't</a>
	<a class="c-button-group__item c-button" href="Button">Let go</a>
	<a class="c-button-group__item c-button" href="Button">Jack</a>
</div>

<div class="c-button-group c-button-group--gutter-small u-margin-bottom">
	<a class="c-button-group__item c-button" href="Button">Don't</a>
	<a class="c-button-group__item c-button" href="Button">Let go</a>
	<a class="c-button-group__item c-button" href="Button">Jack</a>
</div>

<div class="c-button-group c-button-group--gutter u-margin-bottom">
	<a class="c-button-group__item c-button" href="Button">Don't</a>
	<a class="c-button-group__item c-button" href="Button">Let go</a>
	<a class="c-button-group__item c-button" href="Button">Jack</a>
</div>

<div class="c-button-group c-button-group--gutter-large u-margin-bottom">
	<a class="c-button-group__item c-button" href="Button">Don't</a>
	<a class="c-button-group__item c-button" href="Button">Let go</a>
	<a class="c-button-group__item c-button" href="Button">Jack</a>
</div>

<div class="c-button-group c-button-group--gutter-huge">
	<a class="c-button-group__item c-button" href="Button">Don't</a>
	<a class="c-button-group__item c-button" href="Button">Let go</a>
	<a class="c-button-group__item c-button" href="Button">Jack</a>
</div>
```

## Nested Groups

Nesting button groups are super simple just change the parent button to a div and place your button group inside.

```html
<div class="c-button-group c-button-group--gutter">
	<div class="c-button-group__item">
		<div class="c-button-group c-button-group--round c-button-group--border">
        	<a class="c-button-group__item c-button" href="Button">T</a>
        	<a class="c-button-group__item c-button" href="Button">O</a>
        	<a class="c-button-group__item c-button" href="Button">O</a>
        	<a class="c-button-group__item c-button" href="Button">L</a>
        </div>
	</div>
	<div class="c-button-group__item">
		<div class="c-button-group c-button-group--round c-button-group--border">
			<a class="c-button-group__item c-button" href="Button">B</a>
			<a class="c-button-group__item c-button" href="Button">A</a>
			<a class="c-button-group__item c-button" href="Button">R</a>
		</div>
	</div>
</div>
```