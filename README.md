# Progress Bars [![Build Status](https://travis-ci.org/cferdinandi/progress-bars.svg)](https://travis-ci.org/cferdinandi/progress-bars)
Simple CSS progress bars. [View the demo](http://cferdinandi.github.io/progress-bars/).

**In This Documentation**

1. [Getting Started](#getting-started)
2. [Browser Compatibility](#browser-compatibility)
3. [How to Contribute](#how-to-contribute)
4. [License](#license)
5. [Changelog](#changelog)



## Getting Started

Compiled and production-ready code can be found in the `dist` directory. The `src` directory contains development code.

### 1. Include Progress Bars on your site.

```html
<link rel="stylesheet" href="css/progress-bars.css">
```

Progress Bars is [built with Sass](http://sass-lang.com/) for easy customization. If you don't use Sass, that's ok. The `css` folder contains compiled vanilla CSS.

The `_config.scss` and `_mixins.scss` files are the same ones used in [Kraken](http://cferdinandi.github.io/kraken/), so you can drop the `_progress-bars.css` file right into Kraken without making any updates. Or, adjust the variables to suit your own project.

### 2. Add the markup to your HTML.

Use percentages to set the widths of each bar. Add optional `.progress-bar-secondary`, `.progress-bar-success`, `.progress-bar-danger`, or `.progress-bar-warning` classes for additional colors, and to convey meaning.

```html
<div class="progress">
    <div class="progress-bar" style="width: 90%;">
        Basic
    </div>
</div>

<div class="progress">
    <div class="progress-bar progress-bar-secondary" style="width: 30%;"></div>
    Secondary
</div>

<div class="progress">
    <div class="progress-bar progress-bar-success" style="width: 80%;">
    	Success
    </div>
</div>

<div class="progress">
    <div class="progress-bar progress-bar-danger" style="width: 60%;">
    	Danger
    </div>
</div>

<div class="progress">
    <div class="progress-bar progress-bar-warning" style="width: 70%;">
    	Warning
    </div>
</div>
```

And that's it, you're done. Nice work!



## Browser Compatibility

Progress Bars works in all modern browsers, and IE 6 and above.



## How to Contribute

In lieu of a formal style guide, take care to maintain the existing coding style. Don't forget to update the version number, the changelog (in the `readme.md` file), and when applicable, the documentation.



## License

Progress Bars is licensed under the [MIT License](http://gomakethings.com/mit/).



## Changelog

* v2.1.0 - June 23, 2014
    * Converted to gulp.js workflow.
    * Updated naming conventions.
    * Added minified versions of files.
    * Updated to three number versioning system.
* v2.0 - December 6, 2013
	* Renamed from Bar Graph to Progress Bars.
	* Added support for success, danger and warning colors.
	* Added Sass support.
* v1.1 - June 7, 2013
	* Switched to MIT license.
* v1.1 - March 29, 2013
	* Added missing `.graph-bar-alt` color.
* v1.0 - March 14, 2013
	* Initial release.