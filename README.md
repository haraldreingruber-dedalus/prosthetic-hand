
# 🖑 prosthetic-hand 🖑


A very early WIP of a library to emulate mouse/touch/pointer events, designed to help
unit-test touch gestures.





## Build & test

Run `npm install`, then `npm start`, then point your favourite web browser at
`http://localhost:4567/demos/`

Please note that in order to emulate `TouchEvent`s or `PointerEvent`s, your
web browser must support (or polyfill) these events. Short version: use
Chrome with running code that emulates `TouchEvents`, and IE11 or Edge when
emulating `PointerEvent`s.




## TODO

* <s>Implement `TouchEvent`s</s>
* <s>Test multi-finger `TouchEvent`s</s>
* <s>Implement `PointerEvent`s</s>
* Test multi-finger `PointerEvents`s
* <s>Move the timing loop out of `Finger` and into `Hand`</s>
* Allow setting the refresh time of the timing loop / sync to frames
* Add a delay option to `Finger.up()` and `Finger.down()`
* Allow to sync fingers (maybe via `Hand.syncFungers()` and/or ``
* <s>Get some inspiration from https://github.com/hammerjs/simulator/blob/master/index.js</s>
* Implement some kind of wheel-scrolling
* Implement `Hand`-level gestures (pinch, rotate, 2-, 3-, 4-finger pan)
* Implement `ctrlKey`, `metaKey` and `shiftKey` event properties
