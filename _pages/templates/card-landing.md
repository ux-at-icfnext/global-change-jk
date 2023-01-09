---
layout: template
categories: [templates, card-landing]
type: [sub-nav-item]
title: Card Landing Page Template
permalink: /templates/card-landing/
prototype: 
  - name: Agencies Landing Page
    link: "/prototype/agencies/"
overview: The Card Landing template is used for landing pages that utilize the card component to display a list of content. Each card links to a details page for that specific item.
description: The Card Landing template is used for landing pages that utilize the card component to display a list of content. Each card links to a details page for that specific item.

specs:
    - name: Title
      type: h1
      authored: yes
      content: 80 characters max
      searchable: yes
    - name: List
      type: usa-card
      authored: yes
      content: multi-valued see table below
      searchable: yes
specs2:
    - name: Card Image
      type: image
      authored: yes
      content: ratio 1:1
      searchable: yes    
    - name: Card Title
      type: h5
      authored: yes
      content: 80 characters max
      searchable: yes
---

### Card item
{% include partials/content-specs.md content=page.specs2 %} 

## Functionality Specifications
This section shows the details on how to build the page based on the author selections.

