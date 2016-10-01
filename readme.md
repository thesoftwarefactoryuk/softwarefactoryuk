Description
===========

This is the web project for [The Software Factory Limited UK](https://github.com/thesoftwarefactoryuk/thesoftwarefactory.uk.git).


Deploy
======

```
$ heroku login
$ heroku git:remote -a thesoftwarefactoryuk
$ heroku buildpacks:set https://github.com/kr/heroku-buildpack-go.git
$ git add .
$ git commit -am "#1"
$ git push heroku master
$ app deployed to Heroku
```

License
=======