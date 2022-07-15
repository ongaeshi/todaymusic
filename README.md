# day
A simple blog where you can only write one article a day

## Deploy
1. Fork to your reposiytory.
2. Checkout.
```
$ git checkout https://github.com/yourname/day.git
$ mkdir day
```
3. Change `_config.yml` to your environment.

## Test locally
```
$ bundle install
$ ruby ./days_to_posts.rb
$ jekyll serve --watch
```
