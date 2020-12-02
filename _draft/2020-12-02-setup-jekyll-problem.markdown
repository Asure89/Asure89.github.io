---
layout: post
title:  "Understand Git with Three Charts"
date:   2020-12-02 19:10:48 +0100
categories: DevOps Basic
permalink: /:categories/:day/:year/:month/:title.html
---
1. Blank page on Github.
  - See if there is an E-mail referring to the build error. 
  - My problem: The theme I used doesn't supported by Github.
  - Check the instruction on the page of the theme.
  - Add *jekyll-remote-theme* to Gemfile and _config.yml

2. Cannot add custom images
  - every time that the site is built, the files in _site will be renewed.
  - save my images in another folder.
  - How do I know where the background picture is defined?
  - $`bundle bundle info --path jekyll-theme-*`  find the hidden local path of the installed jekyll theme
  - Read `_config.yml` and find corresponding keys.
  - Get to know the file structure


