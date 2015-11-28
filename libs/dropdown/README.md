<p class="u-text-emphasize">This library is base for creating dropdown menus.</p>

Dropdowns base comes with very minimal structural and color styles making it very easy to extend and create your own styles.

*Note: Javascript coming soon for this library.*

```html
<div class="c-dropdown">
	<a class="c-dropdown__action c-button" href="#" title="Action">Action</a>
    <div class="c-dropdown__content">
        <ul>
            <li>Item</li>
            <li>Item</li>
            <li>Item</li>
        </ul>
    </div>
</div>    
```

## Alignment

To set the direction of the dropdown content, use `c-dropdown--right`, `c-dropdown--left`, `c-dropdown--right`, `c-dropdown--right`.

```html
<div class="c-dropdown c-dropdown--top">
	<a class="c-dropdown__action c-button" href="#" title="Top">Top</a>
    <div class="c-dropdown__content u-padding-small">
        <p>Content</p>
    </div>
</div>

<div class="c-dropdown c-dropdown--top-right">
	<a class="c-dropdown__action c-button" href="#" title="Action">Top Right</a>
    <div class="c-dropdown__content u-padding-small">
        <p>Content</p>
    </div>
</div>

<div class="c-dropdown c-dropdown--right">
	<a class="c-dropdown__action c-button" href="#" title="Action">Right</a>
    <div class="c-dropdown__content u-padding-small">
        <p>Content</p>
    </div>
</div>

<div class="c-dropdown c-dropdown--left">
	<a class="c-dropdown__action c-button" href="#" title="Action">Left</a>
    <div class="c-dropdown__content u-padding-small">
        <p>Content</p>
    </div>
</div>

<div class="c-dropdown c-dropdown--bottom">
	<a class="c-dropdown__action c-button" href="#" title="Action">Bottom</a>
    <div class="c-dropdown__content u-padding-small">
        <p>Content</p>
    </div>
</div>

<div class="c-dropdown c-dropdown--bottom-right">
	<a class="c-dropdown__action c-button" href="#" title="Action">Bottom Right</a>
    <div class="c-dropdown__content u-padding-small">
        <p>Content</p>
    </div>
</div>
```

## States

### .is-active

When applied to `.c-dropdown` will set `.c-dropdown__content` to visible.

```html
<div class="c-dropdown is-active">
	<a class="c-dropdown__action c-button" href="#" title="Action">Action</a>
    <div class="c-dropdown__content u-padding-small">
        <p>Content</p>
    </div>
</div>
```