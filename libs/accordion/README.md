# Accordion

The `Accordion` library provides a baseline for expandable and collapsible content that is broken into logical sections.

## Base

##### .c-accordion

Base class for accordion.

```html
<div class="c-accordion">
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Accordion item 1</a>
		</div>
		<div class="c-accordion__content is-active"></div>
	</section>
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Accordion item 2</a>
		</div>
		<div class="c-accordion__content"></div>
	</section>
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Accordion item 3</a>
		</div>
		<div class="c-accordion__content"></div>
	</section>
</div>   
```

##### .c-accordion__item

Base class for accordion items.

```html
<div class="c-card">
	<div class="c-dropdown__header"></div>
</div>   
```

##### .c-accordion__content

Base class for the card content.

```html
<div class="c-accordion">
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Accordion item 1</a>
		</div>
		<div class="c-accordion__content"></div>
	</section>
</div>   
```

##### .c-accordion__header

Base class accordion item header.

```html
<div class="c-accordion">
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Accordion item 1</a>
		</div>
		<div class="c-accordion__content"></div>
	</section>
</div>   
```

##### .c-accordion__content

Base class accordion item content.

```html
<div class="c-accordion">
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Accordion item 1</a>
		</div>
		<div class="c-accordion__content"></div>
	</section>
</div>   
```

## States


##### .is-active

Sets selected item to active and open.

```html
<div class="c-accordion">
	<section class="c-accordion__item">
		<div class="c-accordion__header">
			<a href="#" class="c-accordion__title">Accordion item 1</a>
		</div>
		<div class="c-accordion__content is-active"></div>
	</section>
</div>    
```
