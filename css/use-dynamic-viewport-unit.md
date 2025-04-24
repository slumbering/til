# # Use the new dvh unit for better viewport height handling
Maybe for some of you (like me), dvh, standing for "dynamic viewport height", sounds like a new unit of measurement, but it is not.
It is a new way to measure the viewport height. The dvh unit is a dynamic viewport height unit that takes into account the size of the browser's address bar and other UI elements that may affect the viewport size. This comes very handy when you are working with mobile devices, as the address bar can take up a significant amount of space on the screen.

## How to use dvh
To use dvh, you can simply replace the vh unit with dvh in your CSS. For example, if you want to set the height of an element to 50% of the viewport height, you can use the following code:

```css
.element {
  height: 50dvh;
}
```

This will set the height of the element to 50% of the dynamic viewport height, which will adjust automatically as the address bar and other UI elements change size.

## Browser support
The dvh unit is supported in most modern browsers, including Chrome, Firefox, and Safari.
You can check the current browser support for dvh on [Can I Use](https://caniuse.com/mdn-css_types_length_viewport_percentage_units_dynamic).
