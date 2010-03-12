# CSS3 for SASS

This is a simple SASS file that provides a number of useful mixins to achieve CSS3 effects cross-browser. For each rule, the styles are implemented for as many browsers as possible.

## Rounded Corners

## Syntax

    +round(!radius)
    +round_[top|bottom]_[left|right](!radius)
    +round_[top|bottom|left|right](!radius)

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