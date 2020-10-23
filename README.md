# Pixyll

Pixyll is a simple, beautiful theme for [Hugo](http://gohugo.io/).
Based on [Pixyll for Jekyll](https://github.com/johnotander/pixyll)

[![Netlify Status](https://api.netlify.com/api/v1/badges/a971bc37-c8f3-40d0-ab1b-b28300b4a8d9/deploy-status)](https://app.netlify.com/sites/pixtest/deploys)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/IcpMoles/pyxback&stack=hugo)
[![Import this project into Forestry](https://assets.forestry.io/import-to-forestry.svg)](https://app.forestry.io/quick-start?repo=icpmoles/pyxback&engine=hugo&version=0.72.0)

## How to

Head to the tutorial from the [main blog](https://pyxill2.netlify.app/post/setup-guide/) to discover more.

## Features

- High lighthouse score
- No external services
- Minimal JS use
- Basic tag support.
- Comments powered by Staticman
- Powerful sharing widget.
- Social links (currently only for twitter).
- Pagination support.
- AMP support.
- MathJax support.
- Homepage under 10KiB

### Example config:

```toml
baseURL = "https://example.com/"
absURL= "https://example.com"
languageCode = "en-en"
title = "Pyxill 2"

contentdir = "content"
publishdir = "public"
builddrafts = false
theme = "pyxill2"
ignoreFiles = [ "\\.db$","\\.css$"]
pygmentsUseClassic=false
pygmentsStyle="dracula"
pygmentsCodefences=true
#pygmentsOptions="linenos=table"
Paginate= 10
relativeURLs = false
canonifyURLs= true
[indexes]
  category = "categories"
  tag = "tags"

[params]
  toc= true
  absURL= "https://example.com"
  mainSections = ["post"]
  bg_color= "#3b4252"
  theme_color= "#4c566a"
  twitter_username = "twittersupport"
  paginate = 10
  description = "for the web scraping"
  author = "Author"
  banner= "/banner.png"
# staticman_api = "http://your-staticman-url/v2/connect/GITHUB-USERNAME/GITHUB-REPOSITORY" #Add staticman API URL to enable staticman comments
# RssUrl = "https://feeds.feedburner.com/feed for analytics" 
  
[author]
  name = "The Author"
	
[outputs]
  home = ["HTML", "AMP", "RSS"]
  page = ["HTML", "AMP", "RSS"]

  
[privacy]
  [privacy.instagram]
    disable = false
    simple = true
  [privacy.twitter]
    disable = false
    enableDNT = true
    simple = true
  [privacy.vimeo]
    disable = false
    simple = true
  [privacy.youtube]
    disable = false
    privacyEnhanced = true 
    
[build]
  writeStats = true
  

[markup]
  [markup.goldmark]
    [markup.goldmark.extensions]
      definitionList = true
      footnote = true
      linkify = true
      strikethrough = true
      table = true
      taskList = true
      typographer = true
    [markup.goldmark.parser]
      attribute = true
      autoHeadingID = true
      autoHeadingIDType = "github"
    [markup.goldmark.renderer]
      hardWraps = false
      unsafe = false
      xhtml = false
      

```
## Screenshots


![Pixyll Screenshot](https://raw.githubusercontent.com/IcpMoles/pyxill2/master/images/mobile%20light.png)
![Pixyll Screenshot](https://raw.githubusercontent.com/IcpMoles/pyxill2/master/images/mobile%20dark.png)
![Pixyll Screenshot](https://raw.githubusercontent.com/IcpMoles/pyxill2/master/images/desktop%20light.png)
![Pixyll Screenshot](https://raw.githubusercontent.com/IcpMoles/pyxill2/master/images/desktop%20dark.png)
## Lighthouse Score
![Lighthouse of 100](https://raw.githubusercontent.com/IcpMoles/pyxill2/master/images/Screenshot_20201022-105923~2.png)
