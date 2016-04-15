# Grid Flexbox SASS

Bootstrap 4 inspired CSS3 Flexbox implementation of Responsive Grid.

```html
<div class="row">
    <div class="col-auto">Auto fit column</div>
    <div class="col-20px">Always 20px width</div>
    <div class="col-sm-4 col-md-6">Bigger in large screen</div>
    <div class="col-sm-4 col-md-2">Smaller in large screen</div>
</div>
```

<link href="https://raw.githubusercontent.com/kvdmolen/grid-flexbox-sass/master/dist/gridflexbox.css" rel="stylesheet">

<div class="row">
    <div class="col-auto" style='border:1px solid #EEE'>Auto fit column</div>
    <div class="col-20px">Always 20px width</div>
    <div class="col-sm-4 col-md-6">Bigger in large screen</div>
    <div class="col-sm-4 col-md-2">Smaller in large screen</div>
</div>


Responsive Show and Hide:

```html
<div class="hide-sm">hide-sm: hide from sm and up</div>
<div class="show-sm">hide-sm: show from sm and up</div>
<div class="hide-md">hide-sm: hide from md and up</div>
<div class="show-md">hide-sm: show from md and up</div>
<div class="show-sm hide-md">show-sm hide-md: show from sm and hide from md and up</div>
```

## Features

- Integrated ellipsis
- Stretch columns to full width
- Full height
- Vertical align center (`.col-align-middle`)
- Simple Responsive show & hide system

## Build

    $ sass src/config.scss:dist/gridflexbox.css

## Dependencies

- https://github.com/mastastealth/sass-flex-mixin

## Inspiration

- Bootstrap 4
