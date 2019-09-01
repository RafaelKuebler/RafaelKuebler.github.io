# My Website

## Running
bundle exec jekyll serve


**Updating Placeholder Image**

The placeholder portfolio image can be replaced by the desired image by placing it as `assets/portfolio.png` in your jekyll website.

**Comments (Disqus)**

Comments on posts can be enabled by specifying your disqus_shortname under plainwhite in `_config.yml`. For example,
```yaml
plainwhite:
  disqus_shortname: games
```

**Google Analytics**

It can be enabled by specifying your analytics id under plainwhite in `_config.yml`
```yaml
plainwhite:
  analytics_id: '< YOUR ID >'
```
```yaml
plainwhite:
  sitemap: true
```

**Excerpts**

Excerpts can be enabled by adding the following line to your `_config.yml`
```yaml
show_excerpts: true
```