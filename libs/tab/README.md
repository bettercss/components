<p class="u-text-emphasize">This library is a base for building horizontal or vertical tabbed content.</p>

Tab comes with very minimal structural and color styles making it very easy to extend and create your own styles.

```html
<div class="c-tab">
	<ul class="c-tab__list">
    	<li class="c-tab__item">
    	    <a class="c-tab__link is-active" href="#" title="">Tab</a>
    	</li>
    	<li class="c-tab__item">
    	    <a class="c-tab__link" href="#" title="">Tab</a>
    	</li>
    </ul>
     <div class="c-tab__content is-active">
         <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
     </div>
     <div class="c-tab__content">
         <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
     </div>
</div>    
```

## Alignment

The default alignment behaviour for tab navigation is horizontal, use `.c-tab--vertical` if you require a vertical navigation.

```html
<div class="c-tab c-tab--vertical">
	<ul class="c-tab__list">
     	<li class="c-tab__item">
     	    <a class="c-tab__link is-active" href="#" title="">Tab</a>
     	</li>
     	<li class="c-tab__item">
     	    <a class="c-tab__link" href="#" title="">Tab</a>
     	</li>
    </ul>
    <div class="c-tab__content is-active">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    </div>
    <div class="c-tab__content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    </div>
</div> 
```

## States

### .is-active

When applied to `.c-tab__link` and `.c-tab__content` will make the selected tab in focus and the content visible.

```html
<div class="c-tab">
	<ul class="c-tab__list">
     	<li class="c-tab__item">
     	    <a class="c-tab__link is-active" href="#" title="">Tab</a>
     	</li>
     	<li class="c-tab__item">
     	    <a class="c-tab__link" href="#" title="">Tab</a>
     	</li>
    </ul>
    <div class="c-tab__content is-active">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    </div>
    <div class="c-tab__content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    </div>
</div>
```