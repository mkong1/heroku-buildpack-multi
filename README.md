# heroku-buildpack-multi

Use multiple buildpacks on your app

DDollar is the man

## Usage

    $ heroku buildpacks:set https://github.com/ddollar/heroku-buildpack-multi.git

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-nodejs.git#0198c71daa8
    https://github.com/heroku/heroku-buildpack-ruby.git#v86

## License

MIT
