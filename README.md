# Pixyll

Pixyll is a simple, beautiful theme for [Hugo](http://gohugo.io/).
Based on [Pixyll for Jekyll](https://github.com/johnotander/pixyll)

[![Netlify Status](https://api.netlify.com/api/v1/badges/a971bc37-c8f3-40d0-ab1b-b28300b4a8d9/deploy-status)](https://app.netlify.com/sites/pixtest/deploys)

## Features

- Minimal JS use
- Basic tag support.
- Comments powered by Staticman
- Powerful sharing widget.
- Social links (currently only for twitter).
- Pagination support.
- AMP support.
- MathJax support.

Example config:

```toml
languageCode = "en-us"
contentdir = "content"
publishdir = "public"
builddrafts = false
baseUrl = ""
canonifyurls = true
title = "Pixyll"
author = "admin"
theme = "pixyll"
disqusShortname = "sitename"

[indexes]
  category = "categories"
  tag = "tags"

[params]
  search_engine = true
  google_analytics_id = "XX-XXXXXXXX-X"
  twitter_username = "username"
  paginate = true
```



![Pixyll Screenshot](https://raw.githubusercontent.com/azmelanar/hugo-theme-pixyll/master/images/tn.png)
