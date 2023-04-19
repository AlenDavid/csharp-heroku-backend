# Alen's C# backend deployed in Heroku

## Introduction

This is what you will be doing.

1. Get both heroku and dotnet CLI.
2. Heroku login and heroku create with .Net build pack
3. Set heroku's git remote branch.
4. Commit and push to heroku main.
5. Open your app and good luck!

## Terminal guide

```bash
# edit this line
APP=dotnet-backend
heroku create $APP --buildpack https://github.com/jincod/dotnetcore-buildpack.git
heroku git:remote -a $APP
git push heroku main
# 404 default blank page, please go to /WeatherForecast
heroku apps:open $APP
```
