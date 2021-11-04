# How to debug JavaScript?

## A simple web project example

I use the `console` the console is really powerful in JavaScript - _espacially_ for browser environments.

Let's get started with a very simple example.

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Debugging JavaScript</title>
</head>
<body>
  <h1>Debugging JavaScript</h1>
  <p>Open you browser dev tools to see the console output.</p>
  <script src="./index.js"></script>
</body>
</html>
```

```js
var someObject = {
  foo: {
    bar: {
      baz: 'hello'
    }
  }
};

console.log(someObject);
```

This is how the browser with the open console looks like in Chrome:

![chrome console](./assets/chrome-console.png)

And this is Firefox:

![firefox console](./assets/firefox-console.png)

