# q knockout text

Sass mixin for `background-clip` property &mdash; text that reveals a background image. [Demo](https://0c09c3ca66df96a1bed95976a1c78dcef613007a.htmlb.in)

## Install

    $ bower install q-knockout-text

## Example

```sass
@import "bower_components/q-knockout-text/q-knockout-text";

.example {
  background: url("http://apod.nasa.gov/apod/image/0603/coma_misti.jpg");
  @include q-knockout-text(pink); // this is the text color in non-webkit browsers.
}
```
