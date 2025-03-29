# Icenberg Snippets for VS Code

Snippets to make the WordPress ACF templating tool [Icenberg](https://github.com/maverick-international/Icenberg) even easier to use. 

---

## Features

Snippets are provided for the following common icenberg features:

`ice:init`
```php
$ice = new Icenberg('master_class');
```
---

`ice:el`
```php
$ice->the_element('field_name');
```
---

`ice:get`
```php
$ice->get_element('field_name');
```
---

`ice:field`
```php
$ice->field('field_name');
```
---

`ice:val`
```php
$ice->value('field_name');
```
---

`ice:only`
```php
$ice->field('field_name')->only(['sub_field_name'])->get();
```
---

`ice:except`
```php
$ice->field('field_name')->except(['sub_field_name'])->get();
```
---

### Coming soon

`ice:enclose`
```php
$ice->enclose('class', [
    $ice->get_element($field_name),
]);
```
---

`ice:wrap`
```php
$icenberg::wrap(
    [
        $icenberg->get_element('field_name'),
    ],
    $block,
    true
);
```
---


## Requirements

To use Icenberg you'll need to be using

- ACF Pro
- Icenberg
- WordPress


