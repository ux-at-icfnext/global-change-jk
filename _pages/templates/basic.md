---
layout: template
categories: [templates, basic]
type: [sub-nav-item]
title: Basic Page Template
permalink: /templates/basic/
prototype: 
  - name: Basic
    link: "/prototype/basic-page/"
overview: The basic page template is used for information or documentation.
description: |
  The basic page template is used for information or documentation. It is often the finial destination page in a user's journey.
details: |


specs:
- name: Title
  type: h1
  authored: yes
  content: 80 characters max
  searchable: yes
  source:
  notes: 
- name: Summary
  type: text
  authored: yes
  content: 250 characters max
  searchable: yes
- name: Body
  type: rich text
  authored: yes
  notes: allows h2, h3, h4, bullets, links, icons
---

## Functionality Specifications
This section show the details on how to build the page based on the author selections.

### Page Header
The page header includes the Title and Summary

### Page Body
The page body contains the body Copy with a max width of 80ex.