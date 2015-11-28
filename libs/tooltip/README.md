<p class="u-text-emphasize">This library provides a base for building tooltips.</p>

```html
<a class="c-tooltip c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip</a>
```

## Wrapping

Default behaviour for tooltips text is not to wrap, Use `.c-tooltip--wrap` to wrap the tooltip text after a certain width.

*Note: Default is `200px`.*

```html
<a class="c-tooltip c-tooltip--wrap c-button" href="#" title="Tooltip" data-content="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa">Tooltip</a>
```

## Alignment

To set the direction of the tooltip content, use `.c-tooltip--top`, `c-tooltip--left`, `c-tooltip--right`, `c-tooltip--bottom`.

```html
<a class="c-tooltip c-tooltip--top c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Top</a>
<a class="c-tooltip c-tooltip--left c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Left</a>
<a class="c-tooltip c-tooltip--right c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Right</a>
<a class="c-tooltip c-tooltip--bottom c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Bottom</a>
```

## Spacing

To set the padding on the tooltip content, use `.c-tooltip--tiny`, .c-tooltip--small`, `.c-tooltip--large` or `.c-tooltip--huge`

```html
<a class="c-tooltip c-tooltip--tiny c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Tiny</a>
<a class="c-tooltip c-tooltip--small c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Small</a>
<a class="c-tooltip c-tooltip--large c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Large</a>
<a class="c-tooltip c-tooltip--huge c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Huge</a>
```

## States

### .is-active

When applied to `.c-tooltip` will make the tooltip content visible.

```html
<a class="c-tooltip c-tooltip--right is-active c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip Active</a>
```