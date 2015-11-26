<p class="u-text-emphasize">This library is a base for building forms.</p>

The form base comes with minimal color styling that can be overridden with your own modifier styles.

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
			<label class="c-form__label" for="file">File</label>
			<input id="file" class="c-form__file" type="file" name="file" value="" />
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
			<label class="c-form__label" for="select">Select</label>
			<select id="select" class="c-form__select" name="select" multiple="multiple">
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
			<div class="c-form__radio">
				<input id="radio" class="c-form__input" type="radio" name="radio" value="" placeholder="" />
				<label class="c-form__label" for="radio">Radio</label>
			</div>
		</div>

		<div class="c-form__field">
			<button class="c-button" type="submit">Submit</button>
		</div>

	</fieldset>
</form>
```


