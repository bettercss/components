# Tooltip

The `Tooltip` library allows you to provide additional information about a particular element on the page.

## Base

##### .c-tooltip

Base class for tooltips.

```html
<a class="c-tooltip" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip</a>
```

## Modifiers

##### .c-tooltip--wrap

Wrap text onto a new line after a certain width.

```html
<a class="c-tooltip c-tooltip--wrap" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip</a>
```

### Directional

##### .c-tooltip--[top|left|right|bottom]

Directional class for tooltip.

```html
<a class="c-tooltip c-tooltip--top" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip</a>
```

### Spacing

##### .c-tooltip--[small|large]

Inner spacing for tooltip.

```html
<a class="c-tooltip c-tooltip--small" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip</a>
```

## States

##### .is-active

When a tooltip is in an active state.

```html
<a class="c-tooltip is-active" href="#" title="Tooltip" data-content="This is the tooltip content">Tooltip Active</a>
```