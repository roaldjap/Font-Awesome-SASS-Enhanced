Font Awesome - Enhanced for SASS 3.2
====================================

This Sass version is based on Font Awesome 2.0's CSS (at 22aa51f2).

This Sass sheet does not place any rules/declarations in your stylesheet.
It provides the `icon` mixin, which, when used, ensures that your CSS CSS
only has styles for the icons that you actually need, skipping the ones you
don't.

This version is available at
https://github.com/rstacruz/Font-Awesome-SASS-Enhanced.

Limitations
-----------

In the interest of keeping things small, the only way to use the icons now
are via the `icon` mixin. This sheet doesn't have support for Twitter
Bootstrap anymore.

If you would like to use Font Awesome with Bootstrap (or with
Bootstrap-style usage), please use the official Sass stylesheet.

Usage
-----

Include the font files in your project. You may get them here:
https://github.com/fortawesome/Font-Awesome/tree/master/font

Then in your Sass sheets, simply import `font-awesome` and use the `icon`
mixin.

``` scss
    @import 'font-awesome';

    #menu a {
      @include icon(hand-right);
    }
```

You may also want to set the `$fontAwesomePath` variable to point to the right location.

``` scss
    $fontAwesomePath: 'fonts/fontawesome';
    @import 'font-awesome';
```

-----

Original readme below:

-----

#Font Awesome 2.0
##the iconic font designed for use with Twitter Bootstrap

The full suite of pictographic icons, examples, and documentation can be found at:
http://fortawesome.github.com/Font-Awesome/

##Contact
- Email: dave@davegandy.com
- Twitter: http://twitter.com/fortaweso_me
- Work: Lead Product Designer @ http://kyru.us

##License
Version 2.0 of the Font Awesome font, CSS, and LESS files are licensed under CC BY 3.0:
http://creativecommons.org/licenses/by/3.0/
A mention of 'Font Awesome - http://fortawesome.github.com/Font-Awesome'
in human-readable source code is considered acceptable attribution (most common on the
web). If human readable source code is not available to the end user, a mention in an 'About' 
or 'Credits' screen is considered acceptable (most common in desktop or mobile software).
