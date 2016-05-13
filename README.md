IVSP 420 Capstone
========================================

## Setup

Install [npm][npm-install]. Then, install gulp:

```bash
npm install -g gulp  # May require `sudo`
```

## Developing

```bash
npm install            # One time
gem install scss_lint  # One time
gulp serve
```

## Structure

```bash
├── Gulpfile.js       # Controls Gulp, used for building the website
├── README.md         # This file
├── data.yml          # Metadata associated with the site.
├── dist/             # Gulp builds the static site into this directory
├── package.json      # Dependencies
└── src/              # All source code
    ├── font/         # Font files
    ├── img/          # Images and SVGs
    ├── js/           # Javascript libraries and scripts
    ├── partials/     # Handlebars HTML partials that are included / extended
    ├── sass/         # Stylesheets
    └── templates/    # Handlebars HTML files, one per page on the site.
```

[autoprefixer]: https://css-tricks.com/autoprefixer/
[browsersync]: http://www.browsersync.io/
[cssnano]: http://cssnano.co/
[gulp]: http://gulpjs.com/
[handlebars]: http://handlebarsjs.com/
[htmlmin]: https://github.com/kangax/html-minifier
[imagemin]: https://github.com/imagemin/imagemin
[jscs]: http://jscs.info/
[jshint]: http://jshint.com/
[linting]: https://en.wikipedia.org/wiki/Lint_%28software%29
[npm-install]: https://nodejs.org/en/download/
[uglifyjs]: https://github.com/mishoo/UglifyJS
[scss]: http://sass-lang.com/
[scss-lint]: https://github.com/brigade/scss-lint
