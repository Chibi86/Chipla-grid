Chipla-grid
===========

A Responsive-less-theme
-----------------------

A responsive standalone less theme for Anax-MVC or Chipla-MVC, but you can use as a standalone theme.

License
-------

This software is free software and carries a MIT license.

Use of external libraries
-------------------------

The following external modules are included and subject to its own license.

### lessphp
 * Website: http://leafo.net/lessphp
 * Version included: 0.4.0 (2013-08-09)
 * License: Dual license, MIT LICENSE and GPL VERSION 3
 * Path: `css/chipla-grid/lessphp`
 
### Font Awesome
 * Website: http://fontawesome.io/
 * Version included: 4.7 (2016-10-24)
 * License: SIL OFL 1.1 and MIT LICENSE
 * Path: `css/chipla-grid/font-awesome` and 'fonts'

### Lydia
 * Website: https://github.com/mosbth/lydia
 * Version included: 0.3.x (2013-10-21)
 * License: MIT LICENSE
 * Files: `css/chipla-grid/css3mixins.less` and `css/chipla-grid/mixins.less`
 
### Semantic.gs
 * Website: http://dbwebb-se.github.io/semantic.gs/webroot/ (copy of it)
 * Version included: 1.2 (2012-01-11)
 * License: Apache 2.0 License
 * File: `css/chipla-grid/grid.less`
 
### Normalize.css
 * Website: http://github.com/necolas/normalize.css
 * Version included: 4.1.1 (2016-04-12)
 * License: MIT LICENSE
 * File: `css/chipla-grid/normalize.less`

How to use this theme:
----------------------

### For CHIPLA MVC or Anax-MVC

Add everything to server/project root, except all single files under root (readme.md, license etc) and webroot (index.html, favicon.png etc.)

For adding theme as using theme you need to change to "chipla-grid" as theme name settings, you find it under 'app/config/' and file you us as theme config-file at start "theme.php" can also be "theme-me.php" or "theme-grid.php".
If you don't know which one check in 'webroot/index.php', should be somewhere in top of that file.

Also follow instruction to get lessphp to work.

### For standalone version

If you use php for your project it's only to add everything from webroot path to your webroot path, otherwish you need to change line 7 in index.html from style.php to style.css.
Also follow instruction to get lessphp to work if you use php in your project.

### How to get lessphp to work

Set (writable) CMOD 777 on path 'css/chipla-grid/'.
 
History
-------

### v0.2.0 (2016-11-19)

 * Update Font Awesome from v4.6.3 to v4.7
 
 * Add form-layout
 
 * Change comment to more follow the same form-layout that rest of the page
 
 * Add user pages layout
 
 * Add content, page and blog pages layout
 
 * Add layout for flashmessages use for !(https://github.com/davedoff/Flashmessages-AnaxMVC)[Flashmessages-AnaxMVC]
 
 * Much more...

### v0.1.1 (2016-09-09)

 * Add missing path's and files for Anax MVC / Chipla-MVC.
 
 * Readme: Correction in install instructions.

### v0.1.0 (2016-09-02)

 * First stable version