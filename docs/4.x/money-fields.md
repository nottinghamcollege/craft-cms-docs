# Money Fields

Money fields give you a text input tailored for storing currency amounts.

## Settings

Money fields have the following settings:

- **Currency** – The currency in which values should be stored.
- **Default Value** – The default value that should be applied for new elements.
- **Min Value** – The lowest amount that may be entered in the field.
- **Max Value** – The highest amount that may be entered in the field.
- **Show Currency** – Whether to display the currency label with the field’s text input.
- **Size** – The field’s input width in characters. (Default omits [size](https://www.w3schools.com/tags/att_input_size.asp) attribute.)

## Development

### Querying Elements with Money Fields

### Working with Money Field Data

If you have an element with a Money field in your template, you can access its data using your Number field’s handle:

::: code
```twig
{% set value = entry.myFieldHandle %}
```
```php
$value = $entry->myFieldHandle;
```
:::

That will give you the number value for the field, or `null` if there is no value.

### Saving Money Fields
