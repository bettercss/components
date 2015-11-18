# Feedback

The `Feedback` library provides contextual feedback messages for typical user actions.

## Base

##### .c-feedback

Base class for feedback.

```html
<div class="c-feedback">
	<p>hi, *Waves*</p>
</div>    
```

##### .c-feedback__link

Base class for links within feedback.

```html
<div class="c-feedback">
	<p>hi, <a class="c-feedback__link" href="#">*Waves*</a></p>
</div>    
```

## Modifiers

### Types

##### .c-feedback--[error|success|warning]

Feedback color types.

```html
<div class="c-feedback c-feedback--error">
	<p>hi</p>
</div>   
```

### Spacing

##### .c-feedback--[small|large]

Inner spacing for feedback.

```html
<div class="c-feedback c-feedback--small">
	<p>hi</p>
</div> 
```