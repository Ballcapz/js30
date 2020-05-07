# Day 1

This is to be a reflection on the concepts learned going through JavaScript 30.

## Drum sounds and animations

* The Data tag allows us a good way to define **custom** attributes on our html elements. Any custom attributes must be prefixed by `data-<CUSTOM>`

* Key Code can be extracted from events (e) using `e.keyCode`

* Transitions emit a `transitionend` event that can be tapped into to take some action after an animation is done

## Ideas

This could be used if I wanted to transition a button on click. Say you wanted to open up a part of a page, or reveal more data, you could animate the button and change it throughout the transition and on transitionend (when its all the way open) you could style it back to normal.

Capturing keycodes are useful in in case where keyboard input needs to be captured.

