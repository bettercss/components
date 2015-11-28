<p class="u-text-emphasize">This library provides a base for boxing of dom.</p>

Use the `.c-box` class as a container or to style content regions.

```html
<div class="c-box u-border u-padding">
    <p class="u-margin-bottom-remove">Hey, I'm a Box.</p>
</div>
```

## Links

`.c-box__link` can be used when you need to inherit the color set on `.c-box`.

```html
<div class="c-box u-border u-padding">
    <p class="u-margin-bottom-remove">Hey, I'm a <a class="c-box__link" href="#">Box</a>.</p>
</div>
```

## Scrollable

Use `.c-box--scroll` to apply vertical scroll bars when the content exceeds it height.

```html
<div class="c-box c-box--scroll u-border u-padding" style="height: 100px">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla sagittis neque a dapibus commodo. Nam feugiat fermentum massa, non dignissim mi. Nam dictum faucibus dolor, nec venenatis leo facilisis id. </p>
</div>
```