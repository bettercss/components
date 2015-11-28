<p class="u-text-emphasize">This library is a base for building forms.</p>

Stacked style forms are the default behaviour for this library, but any form layout should be achievable.

```html
<form class="c-form">
	<fieldset class="c-form__fieldset">
		<div class="c-form__field">
			<label class="c-form__label" for="username">Username</label>
			<input id="username" class="c-form__input" type="text" name="username" value="" placeholder="" />
		</div>

		<div class="c-form__field">
			<label class="c-form__label" for="password">Password</label>
			<input id="password" class="c-form__input" type="password" name="password" value="" placeholder="" />
		</div>

		<div class="c-form__field">
			<label class="c-form__label" for="select">Select</label>
			<select id="select" class="c-form__select" name="select">
				<option>One</option>
				<option>Two</option>
				<option>Three</option>
			</select>
		</div>


		<div class="c-form__field">
			<div class="c-form__checkbox">
				<input id="checkbox" class="c-form__input" type="checkbox" name="checkit" value="" placeholder="" />
				<label class="c-form__label" for="checkbox">Check</label>
			</div>
		</div>


		<div class="c-form__field">
			<button class="c-button" type="submit">Submit</button>
		</div>

	</fieldset>
</form>
```

## Inline

You can use the `flex utility` to achieve inline forms.

```html
<form class="c-form">
	<fieldset class="c-form__fieldset">
		<div class="c-form__field">
			<div class="u-flex u-flex-vertical-center u-gutter">
				<label class="c-form__label u-margin-right" for="username">Username</label>
				<input id="username" class="c-form__input u-margin-right" type="text" name="username" value="" placeholder="" />
				<button class="c-button" type="submit">Submit</button>
			</div>
		</div>
	</fieldset>
</form>
```