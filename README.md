# Heroku buildpack: `fastn`

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [fastn](http://fastn.com/). 

## Usage

```
heroku create -b https://github.com/fastn-stack/heroku-buildpack.git

# or if your app is already created
heroku config:add BUILDPACK_URL=https://github.com/fastn-stack/heroku-buildpack.git

git push heroku main
```
