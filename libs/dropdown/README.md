# Dropdown

The `Dropdown` library is a toggleable, contextual menu for displaying content.

## Base

##### .c-dropdown

Base class for dropdowns.

```html
<div class="c-dropdown">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>    
```

##### .c-feedback__action

Base class for the dropdown action.

```html
<div class="c-dropdown">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>    
```

##### .c-feedback__content

Base class for the dropdowns content.

```html
<div class="c-dropdown">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>    
```

## Modifiers

##### .c-feedback--full

Action and content are full width (100%)

```html
<div class="c-dropdown c-dropdown--full">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>   
```

### Directional

##### .c-feedback--[top|top-right|right|left|bottom|bottom-right]

Align dropdown content in direction specified.

```html
<div class="c-dropdown c-dropdown--right">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>   
```

## States

##### .is-active

Open dropdown state.

```html
<div class="c-dropdown is-active">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>   
```