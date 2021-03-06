# Don's Portfolio Site

## About

This is the source code for my portfolio site. The site is currently built using [Jekyll](https://jekyllrb.com/), using the [Phantom](https://github.com/jamigibbs/phantom) theme.


## Developing


### Setup
Clone this repo. Run the following on terminal:
```
gem install bundler
bundle install
bundle exec jekyll serve
```

### Site Generation
Run the following
```
bundle exec jekyll serve
```

Running this generates the site's source code in the `/doc` folder, and hosts the site locally.

### Deploying to Github Pages
Since Github pages doesn't support all of Jekyll's plugins all that well, we'll need to manually perform the bundling to deploy our updated site.
This repo is currently set up to serve files that are in the `/doc` folder.

## Credits

- Phantom, [https://github.com/jamigibbs/phantom](https://github.com/jamigibbs/phantom) (C) 2016, Jami Gibbs, MIT
