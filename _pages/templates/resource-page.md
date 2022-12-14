---
layout: template
categories: [templates, resource]
type: [sub-nav-item]
title: Resource Page Template
permalink: /templates/resource-page/
prototype: 
  - name: Resource PDF
    link: "/prototype/resource-pdf/"
overview: The Resource template is used to give users an overview of a specific resource and a way to access that resource.
description: The Resource template is used to give users an overview of a specific resource and a way to access that resource.

specs:
    - name: Title
      type: h1
      authored: yes
      content: 80 characters max
      searchable: yes
    - name: Date
      type: text
      authored: yes
      content: 150 characters max
      searchable: yes
    - name: Intro Text
      type: text
      authored: yes
      content: ratio 4:1
      searchable:   
    - name: Resource
      type: PDF, Video, Podcast
      authored: yes
    - name: Body
      type: rich text
      authored: yes
      content: 150 characters max
      searchable: yes
    - name: Related Resources
      type: list
      authored: yes
      content:
      searchable: yes
---