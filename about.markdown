# CSS3 for SASS

This is a simple SASS file that provides a number of useful mixins to achieve CSS3 effects cross-browser. For each rule, the styles are implemented for as many browsers as possible.

## Border Radius

**Browser Support:** Firefox, Safari, Chrome, Opera

<dl>
<dt>`+round(10px)`:</dt> <dd>round all four corners 10px</dd>
</dl>
* `+round_[top|bottom]_[left|right](10px)`: round one corner 10px
* `+round_[top|bottom|left|right]`: round two corners (at the top, bottom left or right) 10px