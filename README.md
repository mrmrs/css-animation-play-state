# css-animation-play-state 1.0.6

Css module of single purpose classes for animation play state

#### Stats

200 | 8 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-animation-play-state
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-animation-play-state
```

ssh:
```
git clone git@github.com:tachyons-css/css-animation-play-state.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-animation-play-state";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-animation-play-state@1.0.6/css/css-animation-play-state.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-animation-play-state">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   ANIMATION PLAY STATE
*/
.a-running { -webkit-animation-play-state: running; animation-play-state: running; }
.a-paused { -webkit-animation-play-state: paused; animation-play-state: paused; }
@media screen and (min-width: 48em) {
 .a-running-ns { -webkit-animation-play-state: running; animation-play-state: running; }
 .a-paused-ns { -webkit-animation-play-state: paused; animation-play-state: paused; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .a-running-m { -webkit-animation-play-state: running; animation-play-state: running; }
 .a-paused-m { -webkit-animation-play-state: paused; animation-play-state: paused; }
}
@media screen and (min-width: 64em) {
 .a-running-l { -webkit-animation-play-state: running; animation-play-state: running; }
 .a-paused-l { -webkit-animation-play-state: paused; animation-play-state: paused; }
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

ISC

