---
title: Home
sections:
  - section_id: hero
    component: hero_block.html
    type: heroblock
    content: >-
      A place for Rane Wallin to muse about programming and software development.
  - section_id: about
    component: content_block.html
    type: contentblock
    title: About
    content: >-
      Welcome to my blog. This blog is built from my Dev.to content. My goal is to create
      meaningful and helpful content for other developers. I hope you find something 
      here that helps you!
    actions:
      - label: Contact Me
        url: /contact
  - section_id: recent-posts
    component: posts_block.html
    type: postsblock
    title: Recent Posts
    num_posts_displayed: 4
    actions:
      - label: View Blog
        url: blog/index.html
menus:
  main:
    weight: 1
    title: Home
layout: home
---
