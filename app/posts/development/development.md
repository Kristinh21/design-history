---
tags: false
layout: collection
title: Development
description: Development descriptions and support
pagination:
  data: collections.development
  reverse: true
  size: 50
permalink: "development/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 3
---