# Elastic

Elastic makes your textareas grow and shrink to fit its content. It was inspired by the auto growing textareas on Facebook. The major difference between Elastic and its competitors is its weight.

## How to use Elastic

The usage of Elastic is very straight forward. All you have to do is to include jQuery and the javascript file containing the plugin and use the elastic function.

    $( selector ).elastic();

### Max height

The css property `max-height` will affect Elastic. Scrollbars will appear when the content is bigger than the set max height.

## Change log

| Version | Changes |
| ------- | ------- |
| 1.6.12 | Fixed JSHint errors and added a delay option (By Sunny Walker) |
| 1.6.11 | Fixed an issue with Jquery’s NoConflict-mode and a, mistakenly, omitted var. (Thanks to Adamdicarlo and Weltraumschaf) |
| 1.6.10 | Fixed an issue causing a never ending loop in IE. (Thanks to John, CareerHub) |
| 1.6.9 | Code cleanup and fixed variable leak. (Thanks to Jan Paul Posma) |
| 1.6.5 | Fixed an issue where cut and paste wouldn’t work. (Thanks to Isaac Chapman) |
| 1.6.4 | Fixed issue with minified version and Jquery 1.4.2 |
| 1.6.3 | Fixed issue with continuous spaces and words longer than the width of the textarea (Thanks to Michael A Maw, Eviltwinfletch and Jibum Jung) |
| 1.6.2 | Fixed an issue with max height in Opera (Thanks to Martin Grandrath) |
| 1.6.1 | Fixed a cpu overhead issue, and changed incorrect css selectors to correct ones. (Thanks to Eric Caron, Martin Borthiry and Ara T Howard) |
| 1.6 | Fixed an issue with using elastic on multiple textareas (Thanks to Michael for reporting the bug and finding a solution) |
| 1.5 | Complete refactor of the plugin |
| 1.4 | Fixed an issue regarding disappearing carets |
| 1.3 | Made it compatible with JQuery 1.3.2 and added proper support for max-height (scrollbars visible when textarea reaches max height). The animation is removed. (it took to much visual focus and it did not work well with Google Chrome) (Thanks to Casper Fabricius and Marcus Kabele for contributing to this version) |
| 1.2 | Fixed an issue where the textbox height would twitch when using smaller font sizes. (Thanks to Dimitry for reporting the problem and providing a solution.) |
| 1.1 | Fixed a problem with Internet Explorer 6.0 where the plugin didn’t work if a height attribute in the CSS wasn’t set. (Thanks to Eric for reporting the problem.). |

## License

The MIT License (MIT)

Copyright (c) 2011 Jan Järfalk

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