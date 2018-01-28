# Installation

1. `yarn install`
1. `yarn start`
1. `http://localhost:1234`

# Directory Structure

```js
src/
  index.js
  App.js
  App.css
  Other.js
  Other.css
  WithoutCSS.js
```

You can write plain html in JavaScript files.

```js
// Greeting.js
<div>
  Hello
</div>
```

Custom components are automatically detected.

```js
// App.js
<div>
  <Greeting />
</div>
```

# Troubleshooting

## Port 1234 is already in use

`yarn start --port <other port>`

## Live reload is not working

`yarn start:nocache`

## How to comment

HTML comments are not available.
Use `{/*` and `*/}` instead.

```js
<div>
  {/* comment */}
</div>
```

## CSS is disabled after updating CSS

Save corresponding components.
For example, save App.js after updating App.css.
