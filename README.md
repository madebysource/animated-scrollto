# Animated scrollTo <a href="http://bower.io/search/?q=animated-scrollto"><img src="https://benschwarz.github.io/bower-badges/badge@2x.png" width="130" height="30"></a>

This is a simple function for animating scroll.

- No dependency on extra libraries.
- If user scrolls while animation is running, scroll animation would be immediately canceled.
- Use as a single script or through bower.

## Example usage

```javascript
button.addEventListener('click', function () {
    animatedScrollTo(document.body, 0, 10000);
});
```

This will scroll to top of the page and the animation will run for 10 seconds (1000ms).

## Available on Bower

`bower install animated-scrollto`

## License

MIT
