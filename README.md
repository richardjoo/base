Dev Fu! Base [![build status][ci-image]][ci] [![code quality][cq-image]][cq] [![test coverage][cc-image]][cc]
=============================================================================================================

A template for creating rails 3.2 applications.

## Development

```
$ git clone git@github.com/devfu/base.git
$ cd base
$ bundle
$ cp {sample,}.env                  # edit this file
$ cp Procfile.local{.sample,}       # edit this file
$ cp config/database.yml{.sample,}  # edit this file
$ foreman start -f Procfile.local
$ bundle exec rake db:setup
$ bundle exec rake db:test:prepare
$ bundle exec rspec spec
```

Environment variables are stored in ./.env

<!-- links -->
[cc]: https://coveralls.io/r/devfu/base "test coverage"
[ci]: http://travis-ci.org/devfu/base "build status"
[cq]: https://codeclimate.com/github/devfu/base "code quality"

<!-- images -->
[cc-image]: https://coveralls.io/repos/devfu/base/badge.png
[ci-image]: https://secure.travis-ci.org/devfu/base.png
[cq-image]: https://codeclimate.com/github/devfu/base.png
