# eslint-config-pygz

This package provides pygz's base JS .eslintrc as an extensible shared config.

## Usage

### eslint-config-pygz

Our default export contains all of our ESLint rules, including ECMAScript 6.

First, install this package
```sh
npm install --save-dev eslint-config-pygz eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "pygz"
}
```

### eslint-config-pygz/legacy

For some legacy project using es5.

First, install this package
```sh
npm install --save-dev eslint-config-pygz eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "pygz/legacy"
}
```

### eslint-config-pygz/react
First, install this package and necessary plugins
```sh
npm install --save-dev eslint-config-pygz eslint babel-eslint eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y
```
Then add following contents to your .eslintrc file
```
{
  "extends": "pygz/react"
}
```

## License
MIT
