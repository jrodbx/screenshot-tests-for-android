# How to run the website locally

First time setup:

* You'll need ruby 2 or higher (available by default on Mac)

Then:

```bash
sudo gem install bundler
sudo bundle install
```

## After performing the setup

To build the docs and start a webserver to browse them, and auto-rebuild
as you change content files:

```
jekyll serve -w -t
```

If you've already got a built version of the site, you can save some time
by skipping the initial build.  It will rebuild files when things change:

```
jekyll serve -w -t --skip-initial-build
```

