# Hexo Corporate

Hexo Corporate is a full-featured Hexo theme based on the Metronic Corporate
Frontend freebie framework.  Live example available
[here](http://hexotest.computerlab.io).

This theme is useful for companies interested in using Hexo to create a
professional website with an attractive landing page, company blog, contact
information, and portfolio.  

**Features:**

- custom landing page / index 
- blog posts with tags and categories
- project portfolio
- contact form with google maps
- about page
- swiftype (search) integration
- multiple color schemes
- disqus integration
- social links
- metronic css framework
  [link](http://keenthemes.com/multi-purpose-corporate-frontend-themefreebie-corporate-frontend-theme/)


## Install

``` bash
git clone https://github.com/ptsteadman/hexo-theme-corporate.git themes/corporate;
```

## Enable

1. **Add example pages.** 

	Copy the contents of `themes/corporate/_source` to `_source`. 

	```bash
	cp themes/corporate/_source _source;
	```

2. **Enable custom homepage.**

	Copy the example site config `themes/corporate/_config.site.yml` to the project root, 
	renaming it to `_config.yml`.

	```bash
	cp themes/corporate/_config.site.yml _config.yml;
	```

	Remove the line containing `hexo-generator-index` from `package.json` in the
	project root.

### Update

``` bash
cd themes/corporate
git pull
```

## Configure

Edit `themes/corporate/_config.yml` for theme-specific configuration.

``` yml
# Header
menu:
  Home: /
  Projects: /projects/
  Blog: /blog/
  Contact: /contact/
  About: /about/
   
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Integrations
disqus_shortname: hexothemecorporate
google_analytics: UA-70830587-2
swiftype_install_key: mqSgSxnMMDR4bbs2NXuy

# Social
social:
  github: https://github.com/ptsteadman
  twitter: https://twitter.com/ptsteadman
  facebook: https://www.facebook.com/ptsteadman
  rss: atom.xml
  linkedin: https://linkedin.com/in/ptsteadman
  stackoverflow: http://stackoverflow.com/users/2480493/patrick-steadman

# Miscellaneous
color_scheme: red   # options: blue, gray, green, orange, red, turquoise
favicon: /favicon.ico # path from root of hexo site
twitter_widget_id: "678830341331820544" # as a string, from https://twitter.com/settings/widgets
twitter_username: computerlab_ # twitter username without the app
default_author: Anonymous

about: Computer Lab is a software development and marketing company based in Brooklyn, New York. <br><br> Computer Lab was founded in 2015, and is focused on blah blah blah.
phone: 716-472-4484
email: ptsteadman@gmail.com
address_1: 140 Metropolitan Avenue
address_2: 5th Floor
address_3: Brooklyn, NY 11249
skype: ptsteadman
lat: 40.715911 
long: -73.962147
```

## Metronic Freebie License

The Metronic CSS and JavaScript components are included with the following
license:

```
You are free to use this freebie theme in your any personal or commercial
projects. All used resources, plugins, stock images are subject to thier own
licenses!

The only limitation is that you are not permitted to use this theme in a stock
items that sold in any theme marketplaces(e.g: themeforest.net,
wrapbootstrap.com, etc...).
```

## Features

### Fancybox

Hexo Corporate uses [Fancybox] to showcase your photos. You can use Markdown syntax or fancybox tag plugin to add your photos.

```
![img caption](img url)

{% fancybox img_url [img_thumbnail] [img_caption] %}
```


## Development

### Requirements

- Hexo ??

### Links

