sanchaara.in
============

Code that powers the travel blog at [sanchaara.in](http://sanchaara.in)

## Setting up

### Prerequisites

Ensure Git and [RVM](https://rvm.io/rvm/install) is installed.

### Installation steps

* Install and use `Ruby 2.1`

```
rvm install 2.1 && rvm use 2.1
```

* Install bundler

```
gem install bundler
```

* Install the project dependencies

```
bundle install
```

* Start serving the website

```
bundle exec jekyll serve
```

## Licenses

Different parts of this code base is licensed under different terms. This section explains it in more detail.

The website theme is derived from [mediator](https://github.com/dirkfabisch/mediator), an open source MIT licensed Jekyll theme. All the contents derived from that reside in the following folders and continue to be licensed under the same terms [found here](https://github.com/dirkfabisch/mediator/blob/master/LICENCE).

```
assets/js/
css/
_includes/
_layouts/
_sass/
```

All other files and folders in this project (except _posts/, assets/article_images/ and assets/images/) are released under the MIT license [found here](https://github.com/sandeepraju/sanchaara.in/blob/gh-pages/LICENSE.txt).

The content in the following folders are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

```
_posts/
assets/images/
assets/article_images/
```
