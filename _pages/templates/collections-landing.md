---
layout: template
categories: [templates, collections-landing]
type: [sub-nav-item]
title: Collections Landing Page Template
permalink: /templates/collections-landing/
prototype: 
  - name: Collections Landing
    link: "/prototype/collections-landing-page/"
overview: The Collections Landing template is used for landing pages that utilize the collections component to display a list of content.
description: The Collections Landing template is used for landing pages that utilize the collections component to display a list of content.

specs:
    - name: Title
      type: h1
      authored: yes
      content: 80 characters max
      searchable: yes
    - name: Summary
      type: text
      authored: yes
      content: 250 characters max
      searchable: yes
    - name: Hero
      type: image
      authored: yes
      content: ratio 4:1
      searchable:   
    - name: Body
      type: rich text
      authored: yes
    - name: List
      type: collection component
      authored:
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