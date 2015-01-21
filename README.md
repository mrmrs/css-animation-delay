# CSS ANIMATION DELAY

  Mobile-first classes for an animation-delay scale.
  Set the desired animation-delay on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-animation-delay
```
View on [npm](https://www.npmjs.org/package/css-animation-delay)



## File Size

1.2K animation-delay.css
904B animation-delay.min.css
200B minified and gzipped


## The Code
```
  .a-delay-1 { animation-delay: .5s; }
  .a-delay-2 { animation-delay: 1s; }
  .a-delay-3 { animation-delay: 2s; }
  .a-delay-4 { animation-delay: 4s; }
  .a-delay-5 { animation-delay: 8s; }
  .a-delay-6 { animation-delay: 16s; }


  /* First breakpoint and larger */
@media screen and (min-width: 48em) {
  .a-delay-1-ns { animation-delay: .5s; }
  .a-delay-2-ns { animation-delay: 1s; }
  .a-delay-3-ns { animation-delay: 2s; }
  .a-delay-4-ns { animation-delay: 4s; }
  .a-delay-5-ns { animation-delay: 8s; }
  .a-delay-6-ns { animation-delay: 16s; }
}

  /* Second breakpoint */
@media screen and (min-width: 48em) and (max-width: 64em) {
  .a-delay-1-m { animation-delay: .5s; }
  .a-delay-2-m { animation-delay: 1s; }
  .a-delay-3-m { animation-delay: 2s; }
  .a-delay-4-m { animation-delay: 4s; }
  .a-delay-5-m { animation-delay: 8s; }
  .a-delay-6-m { animation-delay: 16s; }
}

  /* Third breakpoint */
@media screen and (min-width: 64em)  {
  .a-delay-1-l { animation-delay: .5s; }
  .a-delay-2-l { animation-delay: 1s; }
  .a-delay-3-l { animation-delay: 2s; }
  .a-delay-4-l { animation-delay: 4s; }
  .a-delay-5-l { animation-delay: 8s; }
  .a-delay-6-l { animation-delay: 16s; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

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

