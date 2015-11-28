<p class="u-text-emphasize">This library provides feedback messages for typical user actions.</p>

```html
<div class="c-feedback">
	<p class="u-margin-remove">hi, *Waves*</p>
</div>    
```

## Links

`.c-feedback__link` can be used when you need to inherit the color set on `.c-feedback`.

```html
<div class="c-feedback .c-feedback--info">
	<p class="u-margin-remove">hi, <a class="c-feedback__link" href="#">*Waves*</a></p>
</div>
```

## Types

To set contextual types, use `.c-feedback--info`, `.c-feedback--error`, `.c-feedback--success`, `.c-feedback--warning`.

```html
<div class="c-feedback c-feedback--info">
	<p class="u-margin-remove">hi, *Waves*</p>
</div>
<div class="c-feedback c-feedback--error">
	<p class="u-margin-remove">hi, *Waves*</p>
</div>
<div class="c-feedback c-feedback--success">
	<p class="u-margin-remove">hi, *Waves*</p>
</div>
<div class="c-feedback c-feedback--warning">
	<p class="u-margin-remove">hi, *Waves*</p>
</div>
```