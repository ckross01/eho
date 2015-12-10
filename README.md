# eho
> An opinionated JavaScript linter

Requires the following to be added to your `package.json`:

```js
"eslintConfig": {
  "parser": "babel-eslint",
  "extends": [
    "semistandard",
    "standard-react"
  ],
  "ecmaFeatures": {
    "classes": true,
    "jsx": true
  },
  "env": {
    "browser": true,
    "node": true
  },
  "plugins": [
    "react",
    "standard"
  ]
}
```
