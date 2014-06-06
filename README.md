# Animated scrollTo

This is a simple function for animating scroll.

- No dependency on extra libraries.
- If user scrolls while animation is running, scroll animation would be immediately canceled.

## Example usage

```javascript
button.addEventListener('click', function () {
    animatedScrollTo(document.body, 0, 10000);
});
```

This will scroll to top of the page and the animation will run for 10 seconds (1000ms).

## License

MIT
