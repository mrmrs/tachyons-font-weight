# TACHYONS-FONT-WEIGHT

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-font-weight
```
or download the css on github and include in your project.

## The Code
```

/*

   FONT WEIGHT

*/

.fwn { font-weight: normal; }
.b   { font-weight: bold; }
.fw1 { font-weight: 100; }
.fw4 { font-weight: 400; }
.fw9 { font-weight: 900; }

@include break(not-small) {
  .fwn-ns { font-weight: normal; }
  .b-ns   { font-weight: bold; }
  .fw1-ns { font-weight: 100; }
  .fw4-ns { font-weight: 400; }
  .fw9-ns { font-weight: 900; }
}

@include break(medium) {
  .fwn-m { font-weight: normal; }
  .b-m   { font-weight: bold; }
  .fw1-m { font-weight: 100; }
  .fw4-m { font-weight: 400; }
  .fw9-m { font-weight: 900; }
}

@include break(large) {
  .fwn-l { font-weight: normal; }
  .b-l   { font-weight: bold; }
  .fw1-l { font-weight: 100; }
  .fw4-l { font-weight: 400; }
  .fw9-l { font-weight: 900; }
}
```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

