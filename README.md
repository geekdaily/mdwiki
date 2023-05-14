<!-- TODO: get CI running again  -->
<!-- [![Build Status](https://travis-ci.org/Dynalon/mdwiki.png?branch=master)](https://travis-ci.org/Dynalon/mdwiki) -->

MDwiki
======

<!-- TODO: update when/if there's significant difference/progress -->
100% static single file CMS/Wiki done purely with client-side Javascript and HTML5. Here's some [lovely documentation](http://www.mdwiki.info).

## !! This project is currently in experimental/learning mode!!

I'm just learning node and javascript, so I wouldn't rely on this fork if I were you.

Download
--------

<!-- TODO: put up a v0.7.0 release then change this -->
See <https://github.com/Dynalon/mdwiki/releases> for readily precompiled releases.

How to build a clean "distribution" copy from source
----------------------------------------------------

1. Install node and npm
2. Clone the mdwiki repo
3. Install node dependencies: `npm install && npm update`
4. Build MDwiki (you need automake installed - if you are on Windows check the contents of the Makefile for the list of commands to run them manually):

```
    make
```

5. Copy `dist/mdwiki.html` to where you want it installed

How to build a debug/development copy from source
-------------------------------------------------

For development, use

    grunt devel 

To get unminified source code compiled to `dist/mdwiki-debug.html`, as well as auto file watching and livereload support. Symlink the development mdwiki file into your webroot for testing.

<!-- TODO: What's this -->
<!-- [![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/Dynalon/mdwiki/trend.png)](https://bitdeli.com/free "Bitdeli Badge") -->

Things To Do
------------

[] Get rid of bootstrap affix dependency
[] Upgrade to latest bootstrap package
[] move from bootstrap.less to scss
[] remove bootstrap-less package
[] resolve deprecation warning in tsconfig.json
