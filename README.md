Heroku buildpack: Ruby
======================

This is a fork of [Heroku's default buildpack for Ruby](https://github.com/heroku/heroku-buildpack-ruby), extended to support [deft](https://github.com/dtao/deft) as a dependency declaration system. It detects if your app has a **deft.json** file, and if so it automatically installs deft and downloads your dependencies on deployment (so you don't need to include 3rd party libs in your repo).
