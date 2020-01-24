# Crash on touch display contents pointer touch

There is currently an issue which crashes a page at Chromium based browsers (Blink) if an
HTML element is touched that has [display: contents](https://developer.mozilla.org/en-US/docs/Web/CSS/display) and [cursor: pointer](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor) styles associated.
