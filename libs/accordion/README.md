<p class="u-text-emphasize">This library provides a base for building accordions.</p>

Accordions base comes with very minimal structural and color styles making it very easy to extend and create your own styles.

```html
<div class="c-accordion">
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Item</a>
		</div>
		<div class="c-accordion__content "></div>
	</section>
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Item</a>
		</div>
		<div class="c-accordion__content"></div>
	</section>
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Item</a>
		</div>
		<div class="c-accordion__content"></div>
	</section>
</div>   
```

## States

### .is-active

When applied to `.c-accordion__item` will set `.c-accordion__content` to visible for the selected item.

```html
<div class="c-accordion">
	<section class="c-accordion__item is-active">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Item</a>
		</div>
		<div class="c-accordion__content">
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
		</div>
	</section>
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Item</a>
		</div>
		<div class="c-accordion__content"></div>
	</section>
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Item</a>
		</div>
		<div class="c-accordion__content"></div>
	</section>
</div>
```