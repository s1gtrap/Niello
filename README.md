# Niello
Niello is a simple and clean dark mode Theme for "Hugo - Static Site Generator"


# Features

Simple, Clean

Syntax Highlight with highlight.js

Google Adsense

Google Analytics

HTML5 Boilerplate

Dark Mode


# Screenshot
![Theme Screenshot](https://raw.githubusercontent.com/guangmean/Niello/master/images/theme_sc_home.png)

# Installation

In the root of your Hugo site directory run:

```shell
git clone https://github.com/guangmean/Niello.git themes/Niello
```

# Configuration
This is an example of site config.toml:

```toml
baseURL = "https://www.angularcorp.com/"
languageCode = "en-us"
title = "Application Deveopment"
disqusShortname = "yourDisqusShortname" // Add third-party comments system

staticDir = ["static", "themes/Niello/static"]

[params]
keywords = ""   //SEO keywords
description = ""    //Site description
copyright = "&#xA9; 2019 - 2022 by guangmean. All Rights Reserved."
google_ad_client = "ca-pub-******"  //Optional, replace ca-pub-****** with your content
ga = "UA-******" //Optional, replace UA-****** with your content
sharethis = ""  //Optional, Add hou ShareThis appid here

[menu]
    [[menu.niello]]
    name = "Home"
    url = "/"
    weight = 1

    [[menu.niello]]
    name = "About"
    url = "/about/"
    weight = 2
    
```

# Google Adsense & Google Analytics
Niello support Google Adsnese code by configure the google_ad_client param in [params] block and Google Analytics code by the ga param in the site config.toml as abover. 

# ShareThis
Niello support share your content to other platforms by [ShareThis](https://sharethis.com).

# Demo

A fully demo is available here:	[https://www.angularcorp.com](https://www.angularcorp.com) 


