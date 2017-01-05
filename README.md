# Styling the placeholder

Demo version: https://russmaxdesign.github.io/placeholder/

A simple repo to demonstrate how to style the placeholder attribute consistently across common browsers.

The opacity property is used to force Firefox browsers to style the attribute in the same way as Chrome-based browsers.

[Support for the placeholder attribute](http://caniuse.com/#feat=input-placeholder)

```css
::-webkit-input-placeholder {
  opacity: 1;
  color: red;
}

:-moz-placeholder {
  opacity: 1;
  color: red;
}

::-moz-placeholder {
  opacity: 1;
  color: red;
}

:-ms-input-placeholder {
  opacity: 1;
  color: red;
}
```

See [Licence information](LICENCE) for use.
