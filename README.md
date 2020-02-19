Blog published at http://blog.tremblay.pro

# Local installation

```shell script
bundle install
bundle exec jekyll server -w
```

## Run htmlproofer

```shell script
bundle exec jekyll build
bundle exec htmlproofer ./_site --only-4xx --check-favicon --check-html
```

## Upgrade dependencies

```shell script
bundle update
```
# Travis

[![Build Status](https://travis-ci.org/henri-tremblay/henri-tremblay.github.io.svg?branch=master)](https://travis-ci.org/henri-tremblay/henri-tremblay.github.io)

# Developer stuff

[All highlighted languages](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml)
