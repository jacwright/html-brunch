# html-string-brunch

HTML support for brunch. This is a fork of fujimura/html-brunch and the only difference is that this plugin doesn't
wrap the string in a function.

## Usage
Install the plugin via npm with `npm install --save-dev html-brunch` or update your `package.json`.

```html
<div>
  <h1>This is my page</h1>
</div>
```

```javascript
var tmpl = require("./my-page.html");

console.log(tmpl); // "<div>\n  <h1>This is my page</h1>\n</div>"
```

## Release History
See RELEASE_NOTES.md

## License
Copyright (c) 2017 Jacob Wright
Copyright (c) 2013 Fujimura Daisuke
Licensed under the MIT license.
