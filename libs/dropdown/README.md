<p class="u-text-emphasize">This library is base for creating dropdowns menus.</p>

The dropdown base comes with minimal color styling that can be overridden with your own modifier styles.

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

### .c-dropdown--[top|top-right|right|left|bottom|bottom-right]

Aligns `.c-dropdown__content` in the direction specified.

```html
<div class="c-dropdown c-dropdown--right is-active">
	<a class="c-dropdown__action c-button" href="#" title="Action">Action</a>
    <div class="c-dropdown__content u-padding-small">
        <p>Dropdown content</p>
    </div>
</div>
```

## States

##### .is-active

Sets the dropdown into active state.

```html
<div class="c-dropdown is-active">
	<a class="c-dropdown__action c-button" href="#" title="Action">Action</a>
    <div class="c-dropdown__content u-padding-small">
        <p>Dropdown content</p>
    </div>
</div>
```