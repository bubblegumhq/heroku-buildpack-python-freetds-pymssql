Heroku buildpack: Python + FreeTDS + pymssql
============================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for Python + FreeTDS + pymssql, forked from [heroku-buildpack-python](https://github.com/heroku/heroku-buildpack-python/).


Usage
-----

Example usage:

    $ heroku create --buildpack https://github.com/amanjain/heroku-buildpack-python-freetds-pymssql.git

You can also add it to upcoming builds of an existing application:

    $ heroku config:add BUILDPACK_URL=https://github.com/amanjain/heroku-buildpack-python-freetds-pymssql.git