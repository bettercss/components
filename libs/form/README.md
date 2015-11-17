# Form

The `Form` library is a baseline for building complex forms.

## Base

##### .c-form

Base class for forms.

```html
<form class="c-form"></form>
```

##### .c-form__fieldset

Base class for fieldsets.

```html
<fieldset class="c-form__fieldset"></fieldset>
```

##### .c-form__item

Base container class form fields.

```html
<div class="c-form__item">
	<label class="c-form__label">Name:</label>
    <input class="c-form__input" name="name"  value="" />
</div>
```

##### .c-form__label

Base class for labels.

```html
<label class="c-form__label">Label</label>
```

##### .c-form__input

Base class for inputs.

```html
<input class="c-form__input" name="name" value="" />
```
##### .c-form__select

Base class for selects.

```html
<select class="c-form__input" name="name">
	<option>Option</option>
</select>
```
##### .c-form__textarea

Base class for textarea.

```html
<textarea class="c-form_textarea" name="name">Text</textarea>
```

##### .c-form__file

Base class for file upload fields.

```html
<input class="c-form_file" type="file" name="name" />
```

##### .c-form__checkbox

Base class for checkboxes.

```html
<input class="c-form_file" type="checkbox" name="checkbox" /> CheckMe!
```

##### .c-form__radio

Base class for checkboxes.

```html
<input class="c-form_file" type="radio" name="walkietalkie" /> Walkie Talkie
<input class="c-form_file" type="radio" name="walkietalkie" /> Walkie Talkie
```