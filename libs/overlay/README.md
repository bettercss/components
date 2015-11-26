<p class="u-text-emphasize">This library provides a baseline for overlaying content in the viewport or regions.</p>

Example can only be provided for region take over.

### .c-overlay--region

Overlays the container region.

`Note: container requires relative positioning.`


```html
<div style="position:relative;height: 400px;">
	<div class="c-overlay c-overlay--region is-active">
		<div class="c-overlay__content">
			<div class="c-card  u-column-6">
                <div class="c-card__header">
                    <h3 class="u-margin-remove">Header</h3>
                </div>
                <div class="c-card__content">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
                </div>
                <div class="c-card__footer u-text-align-right">
                    <a class="c-button" href="#">Ok</a>
                </div>
            </div>
		</div>
	</div>
</div>
```

### .is-active

Sets an overlay in active state.


### .has-overlay

State class to be applied to the body when overlay `is-active` state.