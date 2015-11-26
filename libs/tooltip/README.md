<p class="u-text-emphasize">This library provide additional information about a particular element on the page.</p>

```html
<a class="c-tooltip c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip</a>
```

### .c-tooltip--wrap

Wrap text onto a new line after a set width default is `200px`.

```html
<a class="c-tooltip c-tooltip--wrap c-button" href="#" title="Tooltip" data-content="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa">Tooltip</a>
```

### .c-tooltip--[top|left|right|bottom]

Direction the tooltip should be positioned.

```html
<a class="c-tooltip c-tooltip--right c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip</a>
```

### .c-tooltip--[small|large]

Set the inner spacing for the tooltip.

```html
<a class="c-tooltip c-tooltip--small c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip</a>
```

### .is-active

Set when tooltip state to active.

```html
<a class="c-tooltip c-tooltip--right is-active c-button" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip Active</a>
```