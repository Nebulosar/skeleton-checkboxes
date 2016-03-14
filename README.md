# skeleton-checkboxes
> Checkboxes for Skeleton CSS

Fairly simple checkbox styles for [Skeleton CSS](http://skeleton-framework.github.io/), inspired by Material Design.

[Demo](http://orbitbot.github.io/skeleton-checkboxes/)

Available on bower and npm with

```bash
$ npm install skeleton-checkboxes
$ bower install skeleton-checkboxes
```

Usage
-----

Add the following html for each checkbox to be styled. The ordering of elements is important because of how the CSS selectors are structured

```html
<input type="checkbox" id="my-checkbox">
<label for="my-checkbox"></label>
```

When using the checkbox styles, if you have a non-white background or for other aesthetic reasons, there might be a need to tune the colors. This can easily be achieved like so: 

```css
input[type="checkbox"]:checked.pink + label {
  background-color: #ff5891;
  border: 1px solid #ff5891;
}
```

Add the matching `class` attribute to the `<input>` element, fe. `<input type="checkbox" class="pink" id="pink-checkbox">`.

Possible future efforts
-----------------------

- evaluate focos effects (zoom?)
