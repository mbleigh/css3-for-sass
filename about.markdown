# CSS3 for SASS

This is a simple SASS file that provides a number of useful mixins to achieve CSS3 effects cross-browser. For each rule, the styles are implemented for as many browsers as possible.

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

    +box_shadow(!x_offset, !y_offset, !blur, !color)

### Browser Support

* Firefox
* Safari
* Chrome
* Opera
* IE (no custom blur amount, no rgba colors)

## Gradients

### Syntax

    +vertical_gradient(!from_color, !to_color)
    +horizontal_gradient(!from_color, !to_color)

### Browser Support

* Firefox
* Safari
* Chrome
* Opera
* IE (only vertical)

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