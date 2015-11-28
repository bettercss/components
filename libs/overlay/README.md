<p class="u-text-emphasize">This library provides a base for overlaying content in the viewport or fixed regions.</p>

*Note: Javascript coming soon.*

## Regions

Use `.c-overlay--region` to take over a specific region of the page.

*Note: container requires relative positioning.*


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

## States

### .is-active

When applied to `.c-overlay` will make the overlay visible.


### .has-overlay

This class works with `.is-active` and should be placed on the html tag to stop background scrolling.