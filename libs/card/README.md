<p class="u-text-emphasize">This library is a flexible and extensible content container which includes options for headers and footers.</p>

The card base comes with minimal color styling that can be overridden with your own modifier styles.

```html
<div class="c-card">
    <div class="c-card__header">
        <h3>Header</h3>
    </div>
    <div class="c-card__content c-card__content--scroll" style="height:100px">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    </div>
    <div class="c-card__footer u-text-align-right">
        <a class="c-button" href="#">Ok</a>
    </div>
</div>
```

### .c-card__content--scroll

Allows the card content to scroll vertical.

```html
<div class="c-card">
    <div class="c-card__header">
        <h3>Header</h3>
    </div>
    <div class="c-card__content c-card__content--scroll" style="height:200px">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    </div>
    <div class="c-card__footer u-text-align-right">
        <a class="c-button" href="#">Ok</a>
    </div>
</div>    
```
