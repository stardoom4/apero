---
title: A Blog That Works
description: |
  This is a fully featured blog that supports categories, 
  tags, series, and pagination.
author: "The R Markdown Team @RStudio"
show_post_thumbnail: true
show_author_byline: true
show_post_date: true
# for listing page layout
layout: list-sidebar # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: A Sidebar for Your Thoughts
  description: |
    This is a fully featured blog that supports categories,
    tags, series, and pagination. Even this sidebar offers 
    a ton of customizations.
    
    Check out the _index.md file in the /blog folder 
    to edit this content. 
  author: "The R Markdown Team @RStudio"
  text_link_label: Subscribe via RSS
  text_link_url: /index.xml
  show_sidebar_adunit: false # show ad container

# set up common front matter for all pages inside blog/
cascade:
  author: "The R Markdown Team @RStudio"
  show_author_byline: true
  show_post_date: true
  show_disqus_comments: false # see disqusShortname in site config
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent posts
    text_link_url: /blog/
    show_sidebar_adunit: false # show ad container
---

