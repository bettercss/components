<p class="u-text-emphasize">This library is a base for displaying content in a manner similar to a playing card.</p>

```html
<div class="c-card">
    <div class="c-card__header u-background-color u-padding-huge">
        <h1 class="u-text-align-center u-margin-remove">Header</h1>
    </div>
    <div class="c-card__content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>

        <a class="c-button" href="#">Button</a>
    </div>
</div>
```

## Headers & Footers

To give the card headers or footers, use `.c-card__header` or `.c-card__footer`.

```html
<div class="c-card">
    <div class="c-card__header">
        <h3 class="u-margin-remove">Header</h3>
    </div>
    <div class="c-card__content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>

    </div>
    <div class="c-card__footer u-text-align-right">
        <a class="c-button" href="#" title="Ok">Ok</a>
    </div>
</div>
```

## Scrollable

Use `.c-card__content--scroll` to apply vertical scroll bars when the content exceeds it height.

```html
<div class="c-card">
    <div class="c-card__header">
        <h3 class="u-margin-remove">Header</h3>
    </div>
    <div class="c-card__content c-card__content--scroll" style="height:200px">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    </div>
</div>    
```
