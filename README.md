AngularJS Cookies
=================

A complete cookies reader/writer Angular Module with full unicode support

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

Requirements
-----

Install [Node.js](http://nodejs.org/) and NPM (should come with)
