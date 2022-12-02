---
layout: template
categories: [templates, Details Page]
type: [sub-nav-item]
title: Details Page Template
permalink: /templates/details/
prototype: 
  - name: Details Page
    link: "/prototype/collections-landing-page/"
overview: The Details Page template is used for providing additional information on a topic. Usually linked to a landing page with broader information.
description: The Details Page template is used for providing additional information on a topic. Usually linked to a landing page with broader information.

specs:
    - name: Title
      type: h1
      authored: yes
      content: 80 characters max
      searchable: yes
    - name: Summary
      type: text
      authored: yes
      content: 150 characters max
      searchable: yes
    - name: Hero
      type: image
      authored: yes
      content: ratio 4:1
      searchable:   
    - name: Body
      type: rich text
      authored: yes
    - name: Search Results
      type: collection component
      authored: yes
      content: 150 characters max
      searchable: yes
    - name: Filters
      type: Accordion
      authored: yes
      content:
      searchable: yes
    - name: Attachments
    - name: Pagination
---