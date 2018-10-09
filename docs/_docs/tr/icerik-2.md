---
title: Writing Posts
permalink: "/docs/tr/icerik-2"
key: docs-writing-posts
---

<!--more-->

## Creating Post Files

To create a new post, all you need to do is create a file in the */_posts* directory. Jekyll requires blog post files to be named like these:

    2011-12-31-new-years-eve-is-awesome.md
    2012-09-12-how-to-write-a-blog.markdown

## Content

All blog post files must begin with YAML Front Matter.

To improve the user experience for both reading and writing posts, TeXt made some enhancements for markdown and some additional styles.

### YAML Front Matter

    ---
    layout: article
    title: Document - Writing Posts
    mathjax: true
    ---