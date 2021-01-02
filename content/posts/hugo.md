---
title: "Hugo"
subtitle: ""
date: 2021-01-03T03:36:31+08:00
lastmod: 2021-01-03T03:36:31+08:00
draft: false
author: ""
description: ""

page:
    theme: "wide"

upd: ""
authorComment: ""

tags: ["Hugo"]
categories: ["Static Web"]

hiddenFromHomePage: false
hiddenFromSearch: false

featuredImage: ""
featuredImagePreview: ""

toc:
  enable: true
math:
  enable: false
lightgallery: false
license: ""
---

# Hugo’s directory structure

* archetypes: Archetypes are content template files that contain preconfigured front matter (date, title, draft). You can create new archetypes with custom preconfigured front matter fields.
  
* assets: Assets folder stores all the files, which are processed by Hugo Pipes. (e.g. CSS/Sass files) This directory is not created by default.
  
* config.toml: Hugo uses the config.toml, config.yaml, or config.json (if found in the site root) as the default site config file. Instead of a single config file, you can use a config directory as well to separate different environments..
  
* content: This is where all the content files live. Top level folders count as content sections. If you have devops and nodejs sections, then you will have content/devops/first-post.md and content/nodejs/second-post.md directories.
  
* data: This directory is used to store configuration files that can be used by Hugo when generating your website.
  
* layouts: Stores templates in the form of .html files. See the Styling section for more information.

* static: Stores all the static content: images, CSS, JavaScript, etc. When Hugo builds your site, all assets inside your static directory are copied over as-is.

* themes: Hugo theme of your choice.



