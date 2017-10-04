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

1. Add everything to server/project root, except all single files under root (readme.md, license etc) and webroot (index.html, favicon.png etc.)

2. For adding theme as using theme ju need to add or change theme configure line to `$app->theme->configure(ANAX_APP_PATH . 'config/theme-grid.php');` in your frontcontroller.

3. Also follow instruction to get lessphp to work.

### For standalone php version

1. Add everything from webroot path to your webroot path.

2. Follow instruction to get lessphp to work if you use php in your project.

### For standalone html version

1. Add everything from webroot path to your webroot path.

2. Change line 7 in index.html from style.php to style.css.

### How to get lessphp to work

Set (writable) CMOD 777 on path `css/chipla-grid/`.
 
History
-------

### v0.3.0 (2017-10-04)

* Added: Design for Forum

* Added: Design for Usermenu

* Added: Design for Breadcrumb

* Added: Design for Paging

* Added: Theme config file for Chipla-MVC or Anax-MVC

* Added: Readonly and disabled design for form

* Edit: Alot rebuild/redesign for better responsive design

* Delete: Font Awesome 4.6.3 files (Deprecated since v0.2.0)

* Update: Install instructions, easier and follow the use of added config file


### v0.2.0 (2016-11-19)

 * Update Font Awesome from v4.6.3 to v4.7
 
 * Add form-layout
 
 * Change comment to more follow the same form-layout that rest of the page
 
 * Add user pages layout
 
 * Add content, page and blog pages layout
 
 * Add layout for [Flashmessages-AnaxMVC](https://github.com/davedoff/Flashmessages-AnaxMVC)
 
 * Much more...
 

### v0.1.1 (2016-09-09)

 * Add missing path's and files for Anax MVC / Chipla-MVC.
 
 * Readme: Correction in install instructions.
 

### v0.1.0 (2016-09-02)

 * First stable version
 
 
```
Copyright (c) 2016 Rasmus Berg, rasmus.berg@chibidesign.se
```