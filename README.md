Instead of

```html
<a style="color: tomato; font-weight: bold; text-align: right;">Hello</a>
```

you do:

```html
<a class="tomato bold right">Hello</a>
```

Just add it to your HTML:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/yegor256/drops@gh-pages/drops-css.min.css"/>
  </head>
</html>
```

Here is a full list of "drops":

| CSS class | Style |
|---|---|
| bold | font-weight: bold; |
| italic | font-style: italic; |
| monospaced | font-family: monospaced; |
| right | text-align: right; |
| left | text-align: left; |
| center | text-align: center; |

## How to contribute

Fork repository, make changes, send us a pull request. We will review
your changes and apply them to the `master` branch shortly, provided
they don't violate our quality standards. To avoid frustration, before
sending us your pull request please run full Grunt build:

```
$ npm install
$ npm test
```

