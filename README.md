# Ractive.js slidehorizontal transition plugin

A horizontal slide transition seems as useful as a vertical one...

This transition has an alias by the name of 'slideh', so you can do
``` html
<div intro="slideh: {easing: 'easeIn'}">
```
as well as
``` html
<div intro="slidehorizontal: {easing: 'easeIn'}">
```

[See the demo here.](http://zenflow.github.io/ractive-transitions-slidehorizontal/)

*Find more Ractive.js plugins at [docs.ractivejs.org/latest/plugins](http://docs.ractivejs.org/latest/plugins)*

## Usage

Include this file on your page below Ractive, e.g:

```html
<script src='lib/ractive.js'></script>
<script src='lib/ractive-transitions-slidehorizontal.js'></script>
```

Or, if you're using a module loader, require this module:

```js
// requiring the plugin will 'activate' it - no need to use the return value
require( 'ractive-transitions-slidehorizontal' );
```



## License

Copyright (c) 2015 Matthew Francis Brunetti. Licensed MIT

Created with the [Ractive.js plugin template](https://github.com/ractivejs/plugin-template) for Grunt.
