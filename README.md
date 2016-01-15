# css-animation-play-state 0.0.7

Css module of single purpose classes for animation play state

#### Stats

186 | 8 | 8
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-animation-play-state
```

#### With Git

```
git clone https://github.com/tachyons-css/css-animation-play-state
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-animation-play-state";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-animation-play-state">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   ANIMATION PLAY STATE
*/
.a-running { animation-play-state: running; }
.a-paused { animation-play-state: paused; }
@media screen and (min-width: 48em) {
 .a-running-ns { animation-play-state: running; }
 .a-paused-ns { animation-play-state: paused; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .a-running-m { animation-play-state: running; }
 .a-paused-m { animation-play-state: paused; }
}
@media screen and (min-width: 64em) {
 .a-running-l { animation-play-state: running; }
 .a-paused-l { animation-play-state: paused; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

