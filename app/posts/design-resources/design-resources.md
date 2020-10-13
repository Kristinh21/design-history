---
tags: false
layout: collection
title: Design Resources
description: A service for .....
related:
  items:
  - text: Prototype
    description: |
      Username: `username`
      Password: `password`
    href: https://...
  - text: User needs
    href: /design-resources
pagination:
  data: collections.design-resources
  reverse: true
  size: 50
permalink: "design-resources/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 3
---
