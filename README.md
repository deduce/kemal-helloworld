# kemal-helloworld

# Requirements

* Crystal Language
* Kemal

# Installation

macOS & Homebrew. Clone this repository & run the following commands in this repo.

```
brew update
brew install crystal-lang
shards install
crystal app.cr
```

# Performance

The most impressive part to me is the response time:

```
[development] Kemal is ready to lead at http://0.0.0.0:3000
2017-04-22 22:59:51 +0800 200 GET / 2.47ms
2017-04-22 22:59:53 +0800 200 GET / 51.0µs
2017-04-22 22:59:54 +0800 200 GET / 35.0µs
2017-04-22 22:59:54 +0800 200 GET / 25.0µs
2017-04-22 22:59:55 +0800 200 GET / 88.0µs
2017-04-22 22:59:55 +0800 200 GET / 28.0µs
2017-04-22 22:59:55 +0800 200 GET / 25.0µs
2017-04-22 22:59:57 +0800 200 GET / 24.0µs
2017-04-22 22:59:57 +0800 200 GET / 24.0µs
2017-04-22 22:59:58 +0800 200 GET / 22.0µs
```
