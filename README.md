# Jekyll

## install Jekyll

```
sudo apt install rbenv
sudo apt install ruby-dev
rbenv install 3.1.2

add to Gemfile

gem "jekyll-remote-theme"
gem 'jekyll-seo-tag'
gem "webrick"
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"

jekyll new my-jekyll-site

jekyll serve --host=0.0.0.0 --port 8080


set environment variables in Cloudflare

Variable name: LC_ALL | Value: C.UTF-8
Variable name: LANG | Value: en_US.UTF-8
Variable name: LANGUAGE | Value: en_US.UTF-8
```


