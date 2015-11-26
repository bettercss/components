<p class="u-text-emphasize">This library provides a base for building accordions.</p>

The accordion base comes with minimal color styling that can be overridden with your own modifier styles.

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

### .is-active

When applied to `.c-accordion__item` will change the state to active.

```html
<div class="c-accordion">
	<section class="c-accordion__item is-active">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Item</a>
		</div>
		<div class="c-accordion__content ">
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