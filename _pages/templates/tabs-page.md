---
layout: template
categories: [templates, tabs]
type: [sub-nav-item]
title: Assessment Page Template
permalink: /templates/assessment-page/
prototype: 
  - name: Assessment Page
    link: "/prototype/assessment/"
overview: The Assessments Page template is used to build pages that contain various subpages stored in tabs.
description: The Assessments Page template is used to build pages that contain various subpages stored in tabs.

specs:
    - name: Title
      type: h1
      authored: yes
      content: 80 characters max
      searchable: yes
    - name: Year
      type: date
      authored: yes
      content: format YYYY
      searchable: yes
    - name: About
      type: long text
      authored: yes
      content:
      searchable:   
    - name: Mandate
      type: long text
      authored: yes
    - name: Chapters
      type: list
      authored: yes
      content: multi-valued - see table below
      searchable: yes
    - name: Roles and Responsibilities
      type: list
      authored: yes
      content: multi-valued - see table below
      searchable: yes
    - name: Engagement Summary
      type: long text
      authored: yes
      content:
      searchable:
    - name: Opportunities
      type: list
      authored: yes
      content: multi-valued - see table below
      searchable: yes
    - name: Workshops
      type: list
      authored: yes
      content: multi-valued - see table below
      searchable: yes
    - name: FAQs
      type: list
      authored: yes
      content: multi-valued - see table below
      searchable: yes
    - name: Timeline
      type: list
      authored: yes
      content: multi-valued - see table below
      searchable: yes
specs2: 
  - name: Chapters Lable
    type: short text
    authored: yes
    content: max 80 chars
  - name: Chapter Content
    type: long text
    authored: yes
    content:
specs3: 
  - name: Role Lable
    type: short text
    authored: yes
    content: max 80 chars
  - name: Role Content
    type: long text
    authored: yes
    content:
specs2: 
  - name: Opportunities
    type: h2
    authored: yes
    content:
  - name: List link
    type: href
    authored: yes
    content: distation page url
specs3: 
  - name: Workshops
    type: h2
    authored: yes
    content:
  - name: List link
    type: href
    authored: yes
    content: distation page url
specs2: 
  - name: FAQs
    type: h2
    authored: yes
    content:
  - name: List link
    type: href
    authored: yes
    content: distation page url
specs3: 
  - name: Timeline
    type: h2
    authored: yes
    content:
  - name: List link
    type: href
    authored: yes
    content: distation page url
---

### Chapters List
{% include partials/content-specs.md content=page.specs2 %} 

### Source Report
{% include partials/content-specs.md content=page.specs2 %}

## Functionality Specifications
This section show the details on how to build the page based on the author selections.

### Page Header
The page header includes the page title (h1)

### Body
- Rich text (includes option for pull quotes)
- Max-width 80ex
- Typically includes rich text and optional images
- Allows h2, h3, h4, bullets, links, icons

## Related Resources
Authors can choose up to 9 resources to features from this series.
- Module title - h2 - content: "Related Resources"
- list - page title of related resource - link options to resource page
- url - page link of related resource

## Source Report
Each highlight detail page should have 1 source report to list here.
- Module title - h2 - content: "Source Report"
- list - page title of source report - link options to report page
- url - page link of source report