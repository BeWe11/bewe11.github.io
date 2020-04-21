# Personal Website

Based on the [jekyll-now](https://github.com/barryclark/jekyll-now) template
and inspired by [mojombo's site](https://github.com/mojombo/mojombo.github.io).

## Local Development

To start the local jekyll dev server, run
```
bundle exec jekyll serve
```
and then open a browser tab to
```
http://localhost:4000
```

To update the live website, simply push changes to the github repository,
github takes care to rebuild the site.

## Comments

The `_config.yml` file contains a `category_mappings` variable. This variable
allows mapping of post directories to displayed category names for all posts
inside these directories. Every category whose directory contains no posts will
not be displayed.

To force a line break, end a line with two spaces.

## License

The following directories and their contents are Copyright Benjamin Weigang.
You may not reuse anything therein without my permission:

* posts/
* images/

All other directories and files are MIT Licensed.
