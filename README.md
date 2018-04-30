# svg-loaders
SVG Loading icons and animations

Demo
===========

https://revplit.com/github/demos/svg-loaders-open-source/index

NOTE: Chrome 45 intended to deprecate SMIL icons but has since [suspended](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/5o0yiO440LM%5B126-150%5D) that deprecation.

Usage
===========

```html
<img src="svg-loaders/puff.svg" />
```

The color of an icon can be manipulated by changing the `fill` attribute in the SVG file.

```
<svg fill="#fff" width="140" height="64" viewBox="0 0 140 64" xmlns="http://www.w3.org/2000/svg">
```

Browser support
===========

| Browser | Version |
| --- | --- |
| Chrome | Latest |
| Firefox | Latest |
| Safari | 11.1 |
| Opera | 50 |
| IOS Safari | 11.3 |
| Andoid 5-6x WebView: Chromium  | 62 |
| Blackberry Browser | 10 |
| Opera for Android | 37 |
| Chrome(Android) | 64 |
| Firefox(Android) | 57 |
| UC Browser(Android) | 11.8 |
| Samsung Internet | 6.2 |



Source: http://caniuse.com/#feat=svg-smil

Minify
===========
All SVG files are fairly small in size, but you can make them even smaller by minifying with something like [SVGO](https://github.com/svg/svgo).
