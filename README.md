# Fancybox-rails

[Fancybox](http://fancybox.net/), tastefully bundled for the Rails 3.1 asset pipeline. Sweet!


## Usage

This gem vendors Fancybox 1.3.4 for Rails 3.1 and greater. The files will be added to the asset pipeline and available for you to use.

To enable, add the following line to the file `app/assets/javascripts/application.js` (or other [sprockets](https://github.com/sstephenson/sprockets) manifest):

``` javascript
//= require fancybox
```

Then add the following line to the file `app/assets/stylesheets/application.css` (or other sprockets manifest):

``` css
*= require fancybox
```

### Installation

* Add `fancybox-rails` to your Gemfile
* Run `bundle`

Enjoy!


## License

**fancybox-rails**

Copyright (c) 2011, Phil Cohen github@phlippers.net All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sub-license, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice, and every other copyright notice found in this software, and all the attributions in every file, and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

**Fancybox JS**

Copyright (c) 2008 - 2010 Janis Skarnelis
That said, it is hardly a one-person project. Many people have submitted bugs, code, and offered their advice freely. Their support is greatly appreciated.

Version: 1.3.4 (11/11/2010)
Requires: jQuery v1.3+

Dual licensed under the MIT and GPL licenses:
  http://www.opensource.org/licenses/mit-license.php
  http://www.gnu.org/licenses/gpl.html
