# Nowallet - Quick Bootstrap Website

## Usage

After installation, run `npm install`, and then run `npx gulp vendor`, and finally `npx gulp dev` which will open up a preview of the website in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp sass` compiles SCSS files into CSS
- `gulp minify-css` minifies the compiled CSS file
- `gulp minify-js` minifies the themes JS file
- `gulp copy` copies dependencies from node_modules to the vendor directory

## Copyright and License

Copyright 2018 Nowallet Developers. Code released under the MIT license.
