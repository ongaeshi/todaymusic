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
4. Push to github.com
```
$ git add .
$ git commit -m "Change _config.yml for my environment"
$ git push
```
5. Wait a few minutes for GitHub Actions to finish.
6. Change the Source branch setting of GitHub Pages to gh-pages.
![](https://i.gyazo.com/b658c1560fe784561aacd6fb592b3be0.png)

## Test locally
```
$ bundle install
$ ruby ./days_to_posts.rb
$ jekyll serve --watch
```
