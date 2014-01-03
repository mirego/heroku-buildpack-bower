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

## License

`heroku-buildpack-bower` is © 2014 [Mirego](http://www.mirego.com) and may be freely distributed under the [New BSD license](http://opensource.org/licenses/BSD-3-Clause).  
See the [`LICENSE.md`](https://github.com/mirego/heroku-buildpack-bower/blob/master/LICENSE.md) file.

## About Mirego

Mirego is a team of passionate people who believe that work is a place where you can innovate and have fun. We proudly build mobile applications for [iPhone](http://mirego.com/en/iphone-app-development/ "iPhone application development"), [iPad](http://mirego.com/en/ipad-app-development/ "iPad application development"), [Android](http://mirego.com/en/android-app-development/ "Android application development"), [Blackberry](http://mirego.com/en/blackberry-app-development/ "Blackberry application development"), [Windows Phone](http://mirego.com/en/windows-phone-app-development/ "Windows Phone application development") and [Windows 8](http://mirego.com/en/windows-8-app-development/ "Windows 8 application development") in beautiful Quebec City.

We also love [open-source software](http://open.mirego.com/) and we try to extract as much code as possible from our projects to give back to the community.