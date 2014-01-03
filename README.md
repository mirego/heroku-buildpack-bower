# heroku-buildpack-bower

Install Bower and Bower components

Note that this buildpack is meant to be used with [__heroku-buildpack-multi__](https://github.com/ddollar/heroku-buildpack-multi), you must have node and npm installed before installing this one.

If like us you use Rails, Bower components must be installed before assets are precompiled.

## Usage

```
$ heroku config:add BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git
```

```
// .buildpacks
https://github.com/heroku/heroku-buildpack-nodejs.git
https://github.com/mirego/heroku-buildpack-bower.git
https://github.com/heroku/heroku-buildpack-ruby.git
```