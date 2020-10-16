---
tags: false
layout: collection
title: Service 2
description: A service for users to..
related:
  items:
  - text: Prototype
    description: |
      Username: `username`
      Password: `password`
    href: https://...
  - text: User needs
    href: /service-2
pagination:
  data: collections.service-2
  reverse: true
  size: 50
permalink: "service-2/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 3
---
