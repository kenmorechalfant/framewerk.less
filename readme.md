# Framewerk

A CSS framework built with [LESS](https://github.com/less/less.js). Also includes [normalize.css](https://github.com/necolas/normalize.css).

## Preview

To properly preview the demo HTML file in this repo I recommend you use a static file server such as [http-server](https://github.com/http-party/http-server) or if you have [PM2](https://github.com/Unitech/pm2) installed you can use `pm2 serve --name framewerk-demo`.

## Usage

In your own LESS file, import the main file from this package, `less/framewerk.less`:

```less
@import '../../node_modules/framewerk/less/framewerk.less'
```

Note: you'll have to adjust the path depending on where your LESS file is, relative to `node_modules`.

Then you compile the LESS with your method of choice. The demo pages in this repo let `less.js` do it client-side. For production you'll want to pre-compile.