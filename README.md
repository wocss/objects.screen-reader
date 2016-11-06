> ## This module is DEPRECATED
> This module has been moved to  [trumps.utilities](https://github.com/wocss/trumps.utilities/blob/master/src/_trumps.hide.scss#L32) (and renamed to `.u-hide`)

# Screen reader

> Object

The `wocss-objects-screen-reader` module contains screen-reader `object` for hide elements from users, but no screen readers.

Install using npm:

```sh
$ npm install wocss-objects-screen-reader --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
// dependencies imports

@import '~wocss-objects-screen-reader';
```

Then you can use the `o-screen-reader` class for hide a element:

```html
<h1 class="o-screen-reader">Hidden title</h1>
```

## Dependencies

* [wocss-tools-bem-constructor](https://github.com/wocss/tools.bem-constructor)
