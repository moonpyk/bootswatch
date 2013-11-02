Bootswatch.scss
===============

<<<<<<< HEAD
Bootswatch is a collection of free themes for [Twitter Bootstrap](http://twitter.github.com/bootstrap/). Check it out at [bootswatch.com](http://bootswatch.com).
This fork aims to provide SCSS conversion for [SASS Twitter Bootstrap](https://github.com/jlong/sass-twitter-bootstrap) of all the themes.
=======
Bootswatch is a collection of free themes for [Bootstrap](http://getbootstrap.com/2.3.2/). Check it out at [bootswatch.com](http://bootswatch.com).
>>>>>>> b97fac3fa161f48f49a30e14d38bb9bf0c97a90a

Usage
-----
Head over to [Bootswatch](http://bootswatch.com) and download the `bootstrap.min.css` file associated with a theme. Replace Bootstrap's stylesheet with this file.

The themes are also hosted on [BootstrapCDN](http://www.bootstrapcdn.com/).

For use with Rails, check out [bootswatch-rails](https://github.com/maxim/bootswatch-rails) (Sass) and [twitter-bootswatch-rails](https://github.com/scottvrosenthal/twitter-bootswatch-rails) (LESS). For use with a Yeoman app or with Bower check out [bootswatch-scss](https://github.com/nrub/bootswatch-scss).

Customization
------
Bootswatch is an open source project, and you’re welcome to modify the themes further. If you’re interested, fork or follow the GitHub repository. The files of interest are in the `scss-convert` branch.

<<<<<<< HEAD
Each raw theme consists of two SCSS files. One is `_variables.scss`, which is included by default in SASS Twitter Bootstrap and allows you to customize [these settings](http://twitter.github.io/bootstrap/customize.html#variables). The other is called `_bootswatch.scss` and introduces more extensive structural changes.
=======
Each raw theme consists of two LESS files. One is `variables.less`, which is included by default in Bootstrap and allows you to customize [these settings](http://getbootstrap.com/2.3.2/customize.html#variables). The other is called `bootswatch.less` and introduces more extensive structural changes.
>>>>>>> b97fac3fa161f48f49a30e14d38bb9bf0c97a90a

Check out the README in the [swatchmaker directory](https://github.com/thomaspark/bootswatch/tree/master/swatchmaker) for step-by-step instructions on building your own swatch.

Authors
-------
[Thomas Park](http://github.com/thomaspark)

+ http://thomaspark.me

[Clément Bourgeois](http://github.com/moonpyk) (SCSS Conversion)

+ http://www.moonpyk.net

Thanks
------
[Mark Otto](http://github.com/markdotto) and [Jacob Thornton](http://github.com/fat) for [Bootstrap](https://github.com/twitter/bootstrap).

[John W. Long](https://github.com/jlong) and all contributors of the SASS Twitter Bootstrap port.

[James Taylor](http://github.com/jostylr) for [cors-lite](https://github.com/jostylr/cors-lite).

[Zack Maril](http://github.com/zmaril) for [bootswatch/swatchmaker/watcher.rb](https://github.com/thomaspark/bootswatch/blob/master/swatchmaker/watcher.rb).

[Gerald Hiller](https://twitter.com/geraldhiller) for the favicon.


Copyright and License
----
Copyright 2012 Thomas Park

Copyright 2013 Clément Bourgeois

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
