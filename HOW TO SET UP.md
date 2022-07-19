Go into the WSL if on Windows. The floowing works on Ubuntu 22.04:

```bash
sudo apt-get install ruby ruby-dev rmagic libmagickwand-dev make g++ imagemagick-6.q16
gem install bundler
bundler install
bundler exec jekyll serve
```

Also set `url: http://localhost:4000` in `_config.yml`.
