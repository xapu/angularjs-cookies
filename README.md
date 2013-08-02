AngularJS Cookies
=================

A complete cookies reader/writer [AngularJS](http://angularjs.org/) Module with full unicode support, based on [A little framework](https://developer.mozilla.org/en-US/docs/Web/API/document.cookie) from Mozilla developer Network 

Usage
-----
Include `cookiesModule.js` in your application `index.html`.

```html
<script src="scripts/services/cookiesModule.js"></script>
```

Add the module `cookiesModule` as a dependency to your app module:

```js
var myapp = angular.module('myApp', ['cookiesModule']);
```

Inject Cookies factory in your controller

```js
app.controller('myController', function (Cookies) {
```

Use it
-----

See `cookiesModule.js` for more usage examples

```js
Cookies.setItem(name, value[, end[, path[, domain[, secure]]]])
Cookies.getItem(name)
Cookies.removeItem(name[, path])
Cookies.hasItem(name)
Cookies.keys()
```
