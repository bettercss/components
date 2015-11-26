<p class="u-text-emphasize">This library provides a base for boxing of dom.</p>

The `.c-box` base class doesn't come with any default color styles allowing you to use it as a container without having to override base styles.

```html
<div class="c-box u-border">
    <p>Box mate</p>
</div>
```

### .c-box--scroll

Sets the box `overflow-x` to auto giving the box vertical scrollbars.

```html
<div class="c-box c-box--scroll u-border" style="height: 100px">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
</div>
```