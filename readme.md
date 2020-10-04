# Framewerk

A CSS framework built with [LESS](https://github.com/less/less.js). Also includes [normalize.css](https://github.com/necolas/normalize.css).

## Development / Preview

First compile the less to CSS by running `npm run compile`, which is an alias for `npx lessc less/framewerk.less framewerk.css`. Then serve the `index.html` file, e.g. with  [http-server](https://github.com/http-party/http-server): `npx http-server .`.

## Usage

In your own LESS file, import the main file from this package:

```less
@import "framewerk/less/framewerk.less";
```

Then compile the LESS with your method of choice. For example: 
`npx lessc less/yourstyles.less public/style.css`