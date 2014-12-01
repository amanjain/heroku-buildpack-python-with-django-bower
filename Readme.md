[Heroku Python Buildpack](https://github.com/heroku/heroku-buildpack-python) with [django-bower](https://django-bower.readthedocs.org/en/latest/installation.html) support.
============================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for Python with django-bower support, forked from [heroku-buildpack-python](https://github.com/heroku/heroku-buildpack-python/).

Prerequisite
-----

Install [NodeJS Buildpack](https://github.com/heroku/heroku-buildpack-nodejs.git) using [Heroku Multi Buildpack](https://github.com/ddollar/heroku-buildpack-multi) as described [here](http://www.rawsrc.com/using-django-bower-on-heroku/).


Usage
-----

Example usage:

    $ heroku create --buildpack https://github.com/amanjain/heroku-buildpack-python-with-django-bower.git

You can also add it to upcoming builds of an existing application:

    $ heroku config:add BUILDPACK_URL=https://github.com/amanjain/heroku-buildpack-python-with-django-bower.git