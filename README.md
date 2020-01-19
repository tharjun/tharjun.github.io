# KDE Connect

## Build instruction

```
gem install bundler jekyll
bundle install --path vendor/bundle
```

## Run development

```
bundle exec jekyll serve
```

## Run production

```
bundle exec jekyll build
```

The configuration are located in `_config.yml`. You should also change the path to the theme in Gemfile

## Fetching Developer Blog Posts

Update the planet.ini file

Use the pluto command line tool and pass in the planet configuration

```
$ pluto update planet.ini
```

Generate the posts

```
$ ruby -r 'jekyll/planet' -e 'JekyllPlanet.main'
```

then run jekyll build to build the site.

## KDE Connect Video Promo Assets

The assets, video files and Kdenlive Project File for the promo video is [on share.kde.org](https://share.kde.org/s/syBwRjeWpx6g6Ta?path=%2FVideo%2FKDE%20Connect%2FKDE%20Connect%20Website%20Promo%20Video)


