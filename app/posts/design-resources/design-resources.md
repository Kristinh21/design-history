---
tags: design
layout: collection
title: Design Resources
description: Resources to help aid the design process
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
