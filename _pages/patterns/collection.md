---
layout: pattern
categories: [patterns, buttons]
title: Collection
type: [sub-nav-item]
permalink: /patterns/collection/
overview: A collection of highlight  options.
variations: true
description: |
  A collection displays a compact list of multiple related items like articles or events. The list links each item to its original source.

  The collection component offers users a way to view short descriptions of related content, providing a simple way to access the original source to learn more. 
  
  It’s useful when you want to highlight information like articles, events, or documents that appear elsewhere on your website or from other sources. Each item in the collection includes a headline that links to another page and (optionally) a small image, descriptive text, and metadata such as date, time, byline, and tags. Items in a collection should be related. This could be by publication date (for instance, all the content was posted in the last week), by content type (all articles, events, or blog posts), or by subject (all items relate to the same topic or theme). Be selective about what content you show in each collection. Except in the case of search results, consider limiting the number of items in each collection to six or fewer.
usa-link: "https://designsystem.digital.gov/components/collection/"


jekyll: |

  "{% include patterns/highlights/highlights.md %}"
### Paths to view design and code... 
## designimg: can be used to show an image of the design until a coded version can be created. The htmlpath & csspath should be located in the pattens folder. Read more about creating coded components in /docs/creating-patterns 
# designimg: 
htmlpath: patterns/highlights/highlights.md
csspath: patterns/highlights/index.scss
---