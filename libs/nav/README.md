<p class="u-text-emphasize">This library provides a base for building flexible navigation's.</p>

```html
<nav class="c-nav">
	<a  class="c-nav__link" href="#" title="Item">Item</a>
    <a  class="c-nav__link" href="#" title="Item">Item</a>
</nav>    
```

## Alignment

The default alignment behaviour for navigation is vertical, use `.c-nav--horizontal` if you require a horizontal navigation.

```html
<nav class="c-nav c-nav--horizontal">
	<a  class="c-nav__link u-padding-tiny" href="#" title="Item">Item</a>
    <a  class="c-nav__link u-padding-tiny" href="#" title="Item">Item</a>
</nav>
```

## Spacing

Use `.c-nav--equal` to give all menu items equal spacing of the container width.

```html
<nav class="c-nav c-nav--horizontal c-nav--equal">
	<a  class="c-nav__link" href="#" title="Item">Item</a>
    <a  class="c-nav__link" href="#" title="Item">Item</a>
</nav>    
```