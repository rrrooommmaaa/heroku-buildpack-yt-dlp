# heroku-buildpack-youtube-dl

Steps to install this custom buildpack
======================================
```
heroku config:add BUILDPACK_URL=https://github.com/grcdeepak1/heroku-buildpack-youtube-dl.git
heroku buildpacks:add https://github.com/grcdeepak1/heroku-buildpack-youtube-dl.git --index 1
git commit --allow-empty -m "Trigger Heroku deploy"
git push heroku master
```