# CSS3 for SASS

This is a simple SASS file that provides a number of useful mixins to achieve CSS3 effects cross-browser. For each rule, the styles are implemented for as many browsers as possible.

## Rounded Corners

## Syntax

`+round(10px)` - round all four corners by 10px  
`+round_[top|bottom]_[left|right](10px)` - round one corner by 10px 
`+round_[top|bottom|left|right]` - round two corners (at the top, bottom left or right) by 10px

### Browser Support

* Firefox
* Safari
* Chrome
* Opera

## Drop Shadows

### Syntax

`+box_shadow(!x_offset, !y_offset, !blur, !color):` - create a shadow on the given element with specified params.

### Browser Support

* Firefox
* Safari
* Chrome
* Opera
* IE (no custom blur amount, no rgba colors)