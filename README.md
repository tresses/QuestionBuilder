a javascript based questionnaire builder, forked from [Bootstrap Form Builder](https://github.com/minikomi/Bootstrap-Form-Builder) using [twitter bootstrap](http://twitter.github.com/bootstrap/).

#Question Builder

##What's this?

A Drag-and-drop question form builder 

###What we've done

* Add several question type to facilitate the questionnaire making(especially when you make a survey!)
 
* Add chinese support

* upgrade to bootstrap3

###Notes

* For development & debugging change the data-main for the require script tag in `index.html` 
  to point at `assets/js/main.js`. (Look just before the closing `<body>` tag!)

* Once done, change it back to  build for production using the `build.js` script in the `assets/js/lib`
  folder and [r.js](https://github.com/jrburke/r.js/). Then revert to `assets/js/main-built.js`

* The full command is `r.js -o assets/js/lib/build.js` which should be run from the base directory.

