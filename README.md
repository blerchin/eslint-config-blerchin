# eslint-config-blerchin

## Usage

Three configurations are currently provided:

### eslint-config-blerchin

A baseline for linting ES2015+ projects.

Install via:
```
$ npm install --save-dev eslint eslint-config-blerchin
```

Then in your `.eslintrc`:
```
{
  "extends": "eslint-config-blerchin",
  ... overwrite any rules as necessary ...
}
```

### eslint-config-blerchin/babel

A configuration for projects using [Babel](https://babeljs.io). 

Installation:
```
$ npm install --save-dev eslint eslint-config-blerchin babel-eslint
``` 

eslintrc:
```
"extends": "eslint-config-blerchin/babel"
```

### eslint-config-blerchin/react

A configuration for projects using [React](https://facebook.github.io/react/).
Also uses Babel as the parser.

Installation:
```
$ npm install --save-dev eslint eslint-config-blerchin babel-eslint eslint-plugin-react
```

eslintrc:
```
"extends": "eslint-config-blerchin/react"
```
