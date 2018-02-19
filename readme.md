# sass-media-query 💁‍

> Sass mixin for simple media query breakpoints.

## Install
```console
$ npm install --save sass-media-query
```
or
```console
$ yarn add sass-media-query
```

## Usage
```sass
@import node_modules/sass-media-query/mixin

+desktop
	body
		// body will be red on desktop (<1200px)
		background-color: red

+tablet
	body
		// body will be green on tablet (<992px)
		background-color: green

+phone
	body
		// body will be blue on phone (<768px)
		background-color: blue
```

## Configure
You can configure the breakpoint widths by setting these variables after importing the mixins.
```sass
@import node_modules/sass-media-query/mixin
// These are the default sizes
$desktop-width: 1200px
$tablet-width: 992px
$phone-width: 768px
```

## Why
I'm making this package more for myself.  This is my most used mixin and it's getting annoying looking for, copying, and pasting into new projects.


## License

MIT © [Lukasz Brodowski](http://lukebro.com)
