# Pointer Gestures
> Rich gestures that work on both desktop and mobile

PointerGestures uses PointerEvents to make useful gestures for application
development.

## Events

All events are prefixed with **tk**, to be distinct from other gesture
libraries.

Included events are:
- `tktap` - a pointer moves down and up quickly, preventable with
  `pointerup.preventTap`
- `tkhold` - a pointer is held down
- `tkholdpulse` - fires on an interval while the pointer is held down
- `tkrelease` - a held pointer is released

## Installation

1. Check out the submodule for PointerEvents, and PointerEvents' necessary
submodules. (`git submodule update --init --recursive`).

2. Include PointerGestures/src/pointergestures in your page.

3. PointerGestures will automatically include PointerEvents.

4. Set the `touch-action` of a few elements and see the events fire!
