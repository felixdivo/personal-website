Go into the WSL if on Windows.

```bash
sudo apt-get install ruby ruby-dev rmagic libmagickwand-dev
gem install bundler
bundler install
bundler exec jekyll serve
```

Also set `url: http://localhost:4000` in `_config.yml`.
