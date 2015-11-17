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

##### .c-feedback--right

Align dropdown content right of action.

```html
<div class="c-dropdown c-dropdown--right">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>   
```

##### .c-feedback--left

Align dropdown content left of action.

```html
<div class="c-dropdown c-dropdown--left">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>   
```

##### .c-feedback--top

Align dropdown content top of action.

```html
<div class="c-dropdown c-dropdown--top">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>   
```

##### .c-feedback--top-right

Align dropdown content top right of action.

```html
<div class="c-dropdown c-dropdown--top-right">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>   
```

##### .c-feedback--bottom

Align dropdown content bottom of action.

```html
<div class="c-dropdown c-dropdown--bottom">
	<a class="c-dropdown__action" href="#" title="Action">Action</a>
    <div class="c-dropdown__content"></div>
</div>   
```

##### .c-feedback--bottom-right

Align dropdown content bottom right of action.

```html
<div class="c-dropdown c-dropdown--bottom-right">
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