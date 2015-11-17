# Tab

The `Tab` library is a baseline for building horizontal or vertical tabbed content.

## Base

##### .c-tab

Base class for tabs.

```html
<div class="c-tab"></div>    
```

##### .c-tab__list

Base for list type navigation.

```html
<div class="c-tab">
	<ul class="c-tab__list">
    	<li class="c-tab__item"><a class="c-tab__link" href="#" title="">Tab 1</a></li>
    	<li class="c-tab__item><a class="c-tab__link" href="#" title="">Tab 2</a></li>
    </ul>
    <div class="c-tab__content"></div>
    <div class="c-tab__content"></div>
</div>    
```

##### .c-tab__item

Base for nav item in tab navigation

```html
<li class="c-tab__item><a class="c-tab__link" href="#" title="">Tab</a></li>
```

##### .c-tab__link

Base for list type navigation.

```html
<a class="c-tab__link" href="#" title="">Tab</a>    
```

##### .c-tab__content

Base container for tab content.

```html
<div class="c-tab__content"></div>   
```


## Modifiers

### Directional

##### .c-tab--vertical

Vertical tab navigation.

```html
<div class="c-tab c-tab--vertical">
	<ul class="c-tab__list">
    	<li class="c-tab__item"><a class="c-tab__link" href="#" title="">Tab 1</a></li>
    	<li class="c-tab__item><a class="c-tab__link" href="#" title="">Tab 2</a></li>
    </ul>
    <div class="c-tab__content"></div>
    <div class="c-tab__content"></div>
</div> 
```

## States

##### .is-active

When a tab is in an active state.

```html
<div class="c-tab c-tab--vertical">
	<ul class="c-tab__list">
    	<li class="c-tab__item is-active"><a class="c-tab__link" href="#" title="">Tab 1</a></li>
    	<li class="c-tab__item><a class="c-tab__link" href="#" title="">Tab 2</a></li>
    </ul>
    <div class="c-tab__content is-active"></div>
    <div class="c-tab__content"></div>
</div> 
```