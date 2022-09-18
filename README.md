# Numscrubber.js

> Let's change values of input numbers by dragging the mouse left & right


## Install

[![NPM](https://nodei.co/npm/numscrubberjs.png?mini=true)](https://www.npmjs.com/package/numscrubberjs/)

Include numscrubber.js file
```html
<script src="src/numscrubber.js"></script>
```
or use CDN
```html
<script src="https://unpkg.com/numscrubberjs"></script>
```

## Usage

Just add ```data-numscrubber``` to your input number  

```html
<input data-numscrubber type="number" value="6" min="4" max="50" />
```
and then call  ```init()```

```js
<script>
    Numscrubber.init();
</script>
```
Thats it!

[JSFiddle demo](https://jsfiddle.net/9h3mgsp7/)

![CodePen demo](https://media.giphy.com/media/l0IygGSCTG9xhArXW/giphy.gif)


## Browsers

Works well on all modern browsers.


## Size

1.1 kb minified.


## License

Licensed under the MIT License.
