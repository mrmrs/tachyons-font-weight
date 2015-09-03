# tachyons-font-weight
2.1.0

Performance based css module.

## Install
```
npm install --save-dev tachyons-font-weight
```

or download the css on github and include in your project:

```
git clone git@github.com:mrmrs/tachyons-font-weight
```

## The Code
```
/*

   FONT WEIGHT

*/

.normal   { font-weight: normal; }
.b        { font-weight: bold; }
.thin     { font-weight: 100; }
.book     { font-weight: 400; }
.semibold { font-weight: 500; }
.bold     { font-weight: 600; }
.heavy    { font-weight: 700; }
.ultrabold{ font-weight: 900; }

@media screen and (min-width: 48em) {
  .normal-ns    { font-weight: normal; }
  .b-ns         { font-weight: bold; }
  .thin-ns      { font-weight: 100; }
  .book-ns      { font-weight: 400; }
  .semibold-ns  { font-weight: 500; }
  .bold-ns      { font-weight: 600; }
  .heavy-ns     { font-weight: 700; }
  .ultrabold-ns { font-weight: 900; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .normal-m    { font-weight: normal; }
  .b-m         { font-weight: bold; }
  .thin-m      { font-weight: 100; }
  .book-m      { font-weight: 400; }
  .semibold-m  { font-weight: 500; }
  .bold-m      { font-weight: 600; }
  .heavy-m     { font-weight: 700; }
  .ultrabold-m { font-weight: 900; }
}

@media screen and (min-width: 64em) {
  .normal-l    { font-weight: normal; }
  .b-l         { font-weight: bold; }
  .thin-l      { font-weight: 100; }
  .book-l      { font-weight: 400; }
  .semibold-l  { font-weight: 500; }
  .bold-l      { font-weight: 600; }
  .heavy-l     { font-weight: 700; }
  .ultrabold-l { font-weight: 900; }
}

```

## Author

[mrmrs](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

