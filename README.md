# Skeleton

![skeleton](https://github.com/lasseborly/skeleton/blob/master/images/screenshot.png "Skeleton")

The bone minimum

This is a theme meant as a starting point for development, not as a theme that should ship with you blog or website.

## Features
* __Opinion free__ - Eventually all Hugo features will be implemented without any mark-up bloat so that it's easy to add your own stuff on top of skeleton.

## Getting Started
From the root of you Hugo site clone the theme into `themes/skeleton` by running:

`git clone https://github.com/lasseborly/skeleton.git themes/skeleton`

## Usage
To use Skeleton you must first, from the root of your Hugo site, run either:

`hugo -t skeleton`

or set in you `config.toml`.

`theme = "skeleton"`

## Configuration
You can set the normal Hugo site variables in your `config.toml` but there is also some custom Skeleton variables you can set. This is an example of a full `config.toml`.

```toml
theme = "skeleton"
baseurl = "https://hugosite.com"
languageCode = "en-us"
title = "Skeleton"

[params]
  subtitle = "The bone minimum"
```

## Contributing

1. Fork it
2. Create your feature branch - `git checkout -b my-new-feature-or-fix`
3. Commit your changes - `git commit -am 'Add some feature-or-fix'`
4. Push to the branch - `git push origin my-new-feature-or-fix`
5. Create new Pull Request

## Extra
Take a look at my [docker setup](https://github.com/lasseborly/hugo-development) for developing with Hugo. It's, again, very simple, straight forward and open for contributions.
