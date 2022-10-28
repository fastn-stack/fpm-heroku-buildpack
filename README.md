# Heroku buildpack: FPM

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [FPM Packages](http://fpm.dev/). 

## Usage

```
heroku create -b https://github.com/ftd-lang/fpm-heroku-buildpack.git

# or if your app is already created
heroku config:add BUILDPACK_URL=https://github.com/ftd-lang/fpm-heroku-buildpack.git

git push heroku main
```
