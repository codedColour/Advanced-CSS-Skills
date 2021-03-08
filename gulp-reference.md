Install Node.js & NPM
*********************
Download and install Node.js from nodejs.org
Test with node -v and npm -v to get version installed


Install Gulp Globally
*********************
npm install gulp -g
Test with gulp -v


Change Cmdr directory to project folder
***************************************
C:/MAMP/htdocs/SitePoint Courses/Gulp Workflow (or whatever you've set it up to be)


Install package.json
********************
Ensure you're in the root folder of your project
npm init
Go throught he question prompts (hit enter to accept the default value)


Install Gulp Locally
********************
Ensure you're in the root folder of your project
npm install --save-dev gulp
This installs the node_modules folder in the root directory
Test again with gulp -v to see both the global and local versions


gulpfile.js
***********
Copy the gulpfile.js boilerplate into the root directory


Gulp Packages To Install
************************
npm install --save-dev gulp-plumber gulp-notify run-sequence browser-sync gulp-imagemin imagemin-pngquant imagemin-zopfli jshint gulp-jshint gulp-uglify gulp-concat gulp-sass gulp-autoprefixer gulp-concat-css gulp-clean-css gulp-rename gulp-useref gulp-if gulp-sourcemaps lazypipe gulp-clean gulp-zip gulp-connect-php

The following packages used to be included but are now deprecated:
-> gulp-util - removed altogether with update to Gulp v4
-> gulp-minify-css - replaced with gulp-clean-css
-> request removed altogether to reflect changes in javaScrip (run npm uninstall request)
-> har-validator no longer supported (run npm uninstall har-validator)
-> url-regex (a dependancy of css-concat is unsafe) - removed and replaced with url-regex-safe (run uninstall url-regex and then npm install url-regex-safe --save-dev)

*** use npm outdated to test if any of the installed packages need updating ***

                 