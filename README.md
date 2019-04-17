# Bootstrap 4.3.1 Gulp 4.0.0 Sass Boilerplate

A not so overkill front-end workflow environment or boilerplate.. whatever you want to call it. bootstrap 4.3.1, For gulp 4, sass and BrowserSync using NPM and Gulp. Automatically compiles and minifies Bootstrap, fontawesome, jquery's node_modules files into the dist folder.
Fork, star or use it in your project.

## Pre-requisite

- [Node.js](https://nodejs.org/en/download/ "Node Js")
- NPM (Comes with Node.js)

## Getting started

1. Clone repository:
   `git clone https://github.com/designdust/bootstrap-4-gulp-4-sass-boilerplate.git`

2. Change directory:
   `cd bootstrap-4-gulp-4-sass-boilerplate`
3. Install all dependencies and libraries:
   `npm install`

4. Run Gulp Task:

- `gulp` - To compile scss to css, minify css and js and build ready for production files in **dist** folder.

- `gulp dev` - Starts a local server with browserSync and hot reloading on changes to files (HTML, SCSS, JS).

## Dependencies

```
  "devDependencies": {
    "browser-sync": "^2.26.3",
    "del": "^4.1.0",
    "gh-pages": "^2.0.1",
    "gulp": "^4.0.0",
    "gulp-autoprefixer": "^6.0.0",
    "gulp-clean-css": "^4.0.0",
    "gulp-concat": "^2.6.1",
    "gulp-html-replace": "^1.6.2",
    "gulp-rename": "^1.4.0",
    "gulp-sass": "^4.0.2",
    "gulp-sourcemaps": "^2.6.5",
    "gulp-uglify": "^3.0.2",
    "merge-stream": "^1.0.1"
  },
  "dependencies": {
    "@fortawesome/fontawesome-free": "^5.8.1",
    "bootstrap": "^4.3.1",
    "jquery": "^3.4.0",
    "popper.js": "^1.15.0"
  },
```

## Push to your own repo

Please refer to this stackoverflow answer

- https://stackoverflow.com/a/44076938/6441985
