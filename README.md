#Multi-Direction Twitter Bootstrap-Sass v 3.3.1

Features:
- support both RTL and LTR languages
- separate settings file for each of directions
- RTL direction optimized as default for Persian(farsi) language with specific fonts.

## Installation
------
for installation, just change @import of direction settings BEFORE importing [_bootstrap.scss](assets/stylesheets/_bootstrap.scss).
```sass
@import "rtl"; // or ltr
```
And import js file like this:
```js
require('bootstrap-sass');
```

> For more details about compile & installation, visit [Bootstrap-sass](https://github.com/twbs/bootstrap-sass)

## Settings
------
Settings files for both RTL and LTR exists in `assets/stylesheets/rtl.scss` && `/assets/stylesheets/ltr.scss`.
