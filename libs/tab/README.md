<p class="u-text-emphasize">This library is a baseline for building horizontal or vertical tabbed content.</p>

The tab base comes with minimal color styling that can be overridden with your own modifier styles.

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

### .c-tab--vertical

Tabs with vertical navigation.

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

### .is-active

When a selected tab is in an active state.
