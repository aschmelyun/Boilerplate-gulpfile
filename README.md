## Boilerplate Gulp.js Configuration ##

A simple gulpfile to kick-start your Gulp.js workflow. Current functionality includes:

* Compiling SCSS
* Minifying CSS
* Concatenating JS files
* Minifying JS
* Watching for changes in *.scss and *.js files

The default file structure follows this layout:

    /Project Name
        /build
            /assets
                /css
                    main.css
                    main.min.css
                /js
                    main.js
                    main.min.js
        /src
            /js
                javascript.js
                files.js
                here.js
            /scss
                style.scss
                files.scss
                here.scss
        gulpfile.js

If you're not familiar with Gulp yet, I'd recommend following [this tutorial](http://travismaynard.com/writing/getting-started-with-gulp) for an in-depth instruction on installing Node, NPM, and setting up Gulp. 