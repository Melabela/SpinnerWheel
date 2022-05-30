# SpinnerWheel

An experiment to code and animate a "prize wheel" (often seen in promotions)
 using only HTML5 technologies.  Primarily HTML Canvas, and Javascript.

Single-page design.  Styles (CSS) and Scripts (JS) all inside html file.

### Features

- configurable segments
  - settings on page
  - config can be saved/loaded
- working pointer, which flaps at segment boundaries
- ease-out slowdown, after "Stop..." button is clicked

### Code points

- makes use of Canvas context translation/rotation, to simply drawing operations
- animation done with callback `window.requestAnimationFrame()`
- while wheel is spinning, configuration elements are intentionally locked
- configuration save/load code, uses character-safe bits of ASCII encoding to store values

