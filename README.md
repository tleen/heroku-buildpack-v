# heroku-buildpack-v

Heroku Buildpack for V

[](/img/v-logo.png)

![V lang logo](https://vlang.io/img/v-logo.png)

This is an unofficial [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [V](https://vlang.io).

# V Version

This buildpack uses the current `master` branch of V. This could break things for you, be aware. We hope to add v versioning soon.

# Repository Structure

This buildpack will detect your repository as a V project if you are using a `v.mod` file. This file will also be used to install module dependencies.

The main application should be in the repository root and be declared as the `module main`.

# Default Procfile

If no [Procfile](https://devcenter.heroku.com/articles/procfile) is present in the repository root one will be generated for you. You will have more control using your own Procfile.
