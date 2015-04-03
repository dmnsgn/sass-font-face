# sass-font-face
Font-face mixin for sass

## Install

```bash
$ npm install sass-font-face --save
```

## Usage

```SCSS
@import "../node_modules/sass-font-face/_font-face.scss";

$font-regular: 'Open Sans Regular';

@include font-face($font-regular, 'fonts/', 'OpenSans-Regular-webfont', 'open_sansregular');

.element {
  font-family: $font-regular;
}

```

## License

MIT
