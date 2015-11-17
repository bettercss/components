# Overlay

The `Overlay` library provides a baseline for overlaying content in the viewport or regions.

## Base

##### .c-overlay

Base class for overlays.

```html
<div class="c-overlay">
	<div class="c-overlay__content"></div>
</div>    
```

##### .c-overlay__content

Base class for holding overlay content.

```html
<div class="c-overlay__content"></div>   
```


## State

##### .is-active

When a overlay is in an active state.

```html
<div class="c-overlay is-active">
	<div class="c-overlay__content"></div>
</div> 
```

##### .has-overlay

State class to be applied to the body when overlay `is-active` state.

```html
<html class="has-overlay">
<body>
  <div class="c-overlay is-active">
      <div class="c-overlay__content"></div>
  </div>
</body>
</html>
```