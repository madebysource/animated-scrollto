# Animated scrollTo

This is a simple function for animating scroll.

- No dependency on extra libraries.
- If user scrolls while animation is running, scroll animation would be immediately canceled.
- Use as a single script or through browserify/webpack.

## Browser support

- If you want full browser support include this library: https://github.com/mathiasbynens/document.scrollingElement

## Example usage

```javascript
button.addEventListener('click', function () {
    animatedScrollTo(
        document.body, // element to scroll with (most of times you want to scroll with whole <body>)
        0, // target scrollY (0 means top of the page)
        10000, // duration in ms
        function() { // callback function that runs after the animation (optional)
          console.log('done!')
        }
    );
});
```

This will scroll to top of the page and the animation will run for 10 seconds (10000ms).

## Import as an external script

Just import this library with `<script>` and global function `animatedScrollTo` will be available for you.

## Available with Browserify

`npm install animated-scrollto`

In your browserify/webpack powered js:

```javascript
var animatedScrollTo = require('animated-scrollto')
```

## License

MIT
