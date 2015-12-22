# tachyons-font-weight 2.1.0

Performance based css module.

#### Stats

281 | 32 | 32
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-font-weight
```

#### With Git

```
git clone https://github.com/tachyons-css/tachyons-font-weight
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-font-weight";
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
<link rel="stylesheet" href="path/to/module/css/tachyons-font-weight">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

   FONT WEIGHT

*/
.normal { font-weight: normal; }
.b { font-weight: bold; }
.thin { font-weight: 100; }
.book { font-weight: 400; }
.semibold { font-weight: 500; }
.bold { font-weight: 600; }
.heavy { font-weight: 700; }
.ultrabold { font-weight: 900; }
@media screen and (min-width: 48em) {
 .normal-ns { font-weight: normal; }
 .b-ns { font-weight: bold; }
 .thin-ns { font-weight: 100; }
 .book-ns { font-weight: 400; }
 .semibold-ns { font-weight: 500; }
 .bold-ns { font-weight: 600; }
 .heavy-ns { font-weight: 700; }
 .ultrabold-ns { font-weight: 900; }
}
@media screen and (min-width: 48em) and (max-width: 64em) {
 .normal-m { font-weight: normal; }
 .b-m { font-weight: bold; }
 .thin-m { font-weight: 100; }
 .book-m { font-weight: 400; }
 .semibold-m { font-weight: 500; }
 .bold-m { font-weight: 600; }
 .heavy-m { font-weight: 700; }
 .ultrabold-m { font-weight: 900; }
}
@media screen and (min-width: 64em) {
 .normal-l { font-weight: normal; }
 .b-l { font-weight: bold; }
 .thin-l { font-weight: 100; }
 .book-l { font-weight: 400; }
 .semibold-l { font-weight: 500; }
 .bold-l { font-weight: 600; }
 .heavy-l { font-weight: 700; }
 .ultrabold-l { font-weight: 900; }
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

