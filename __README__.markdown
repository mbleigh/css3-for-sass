# CSS3 for SASS

This is a simple SASS file that provides a number of useful mixins to achieve CSS3 effects cross-browser. For each rule, the styles are implemented for as many browsers as possible.

**Note:** You must use `haml >= 3.0` for this to work as it uses the dollar assignment operator and equals-less assignment. This may mean installing the `--pre` version of HAML until its official release.

# Box Effects

## Rounded Corners

### Syntax

    +border-radius(!radius)
    +border-[top|bottom]-[left|right]-radius(!radius)
    +border-[top|bottom|left|right]-radius(!radius)

### Browser Support

* Firefox
* Safari
* Chrome
* Opera

## Drop Shadows

### Syntax

    +box-shadow(!x_offset, !y_offset, !blur, !color)

### Browser Support

* Firefox
* Safari
* Chrome
* Opera
* IE (no custom blur amount, no rgba colors)

## Gradients

### Syntax

    +vertical-gradient(!from_color, !to_color)
    +horizontal-gradient(!from_color, !to_color)

### Browser Support

* Firefox
* Safari
* Chrome
* Opera
* IE (vertical only)

# Transformations

## Rotate

### Syntax

    +rotate(!degrees)

### Browser Support

* Firefox
* Safari
* Chrome
* Opera
* IE