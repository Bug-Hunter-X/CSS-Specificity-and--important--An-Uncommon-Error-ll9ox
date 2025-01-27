# CSS Specificity and !important: An Uncommon Error

This repository demonstrates an uncommon error in CSS related to specificity and the `!important` declaration. The error arises from unexpected inheritance behavior when using `!important` to override inherited styles.

## Bug Description

The bug occurs when using `!important` to override a style that is inherited from a parent element. The specificity of the `!important` declaration can lead to unexpected results and make debugging difficult. 

## Bug Reproduction

1. Open `bug.css`.
2. Observe the styles applied to the `<a>` tag within the `<p>` tag.
3. The `font-size` of the `<a>` tag is unexpectedly smaller than expected. This unexpected behavior is a result of the `!important` declaration and the inheritance cascade in CSS.