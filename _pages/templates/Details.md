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
    - name: Image
      type: image
      authored: yes
      content: ratio 4:1
      searchable:
    - name: Body
      type: rich text
      authored: yes
      notes: allows h2, h3, h4, bullets, link, icons
    - name: Related Resources
      type: list
      authored:
      content: multi-valued - see table below
      searchable: yes
specs2: 
  - name: List text
    type: text
    authored: yes
    source: distation page title
  - name: List link
    type: href
    authored: yes
    source: distation page url
---

### Related list item
{% include partials/content-specs.md content=page.specs2 %} 

## Functionality Specifications
This section show the details on how to build the page based on the author selections.

### Page Header
The page header includes the page title (h1)

### Body
- Rich text (includes option for pull quotes)
- Max-width 80ex
- Typically includes rich text and optional images
- Allows h2, h3, h4, bullets, link, icons

## Related Resources
Authors can choose up to 9 resources to features from this series.
- Module title - h2 - content: "Related Resources"
- list - page title of related resource - link options to resource page
- url - page link of related resource