None of the existing hugo themes fit what I wanted so I created my own. I'm horrible at front-end stuff and usually stay away from it so keep that in mind if you plan on using this.

Skeleton is the CSS framework used.

# Configuration
This theme will not work out (well, it won't work correctly) of the box, there are a few parameters you'll have to add/set in your main hugo config file.

**config.toml**

``` toml
baseurl = "http://hugo.spf13.com/"
title = "Hugo Themes"
author = "Steve Francia"
copyright = "Copyright (c) 2008 - 2014, Steve Francia; all rights reserved."
canonifyurls = true

[params]
	headerimg = "your header image, this should live in static/img/"
	blogHeader = "HTMLized <b>blog</b> header"
    tagline = "shows up next to your title"
    githubUrl = "your Github URL"
    contactEmail = "email address to use with the contact link"
```

Additionally you will probably want to edit layouts/partials/header.html so that the "about" link points to where you want it to go.   
