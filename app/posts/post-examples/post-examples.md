---
tags: false
layout: collection
title: Post examples
description: Example templates that design, content and user research can use
related:
  items:
  - text: Examples posts from BAT
    href: https://bat-design-history.netlify.app/
pagination:
  data: collections.post-examples
  reverse: true
  size: 50
permalink: "post-examples/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 3
---
