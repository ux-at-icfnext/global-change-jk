---
layout: template
categories: [templates, Details Page]
type: [sub-nav-item]
title: Details Page Template
permalink: /templates/details/
prototype: 
  - name: Agency Details Page
    link: "/prototype/agency-details/"
overview: The Details Page template is used for providing additional information on a topic. Usually secondary to a landing page with broader information.
description: The Details Page template is used for providing additional information on a topic. Usually secondary to a landing page with broader information.

specs:
    - name: Title
      type: h1
      authored: yes
      content: 80 characters max
      searchable: yes
    - name: Date
      type: date
      authored: optional
      content: shows date format "Month DD, YYYY"
      searchable:
    - name: Opening Body
      type: rich text
      authored: yes
      content: recommended 150 word max
      searchable: yes
      notes: allows h2, h3, h4, bullets, link, icons
    - name: Image
      type: image
      authored: yes
      content: ratio 4:1
      searchable:
    - name: Resource Item
      type:
      authored:
      content: types - podcast, video, publication
      searchable:
      notes: read sub pages for each specification for each type
    - name: Body
      type: rich text
      authored: yes
      notes: allows h2, h3, h4, bullets, link, icons
    - name: Related Resources
      type: list
      authored:
      content: multi-valued - see table below
      searchable: yes
---