---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "{{ replace .Name "-" " " | title }}"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: {{ .Date }}
lastmod: {{ .Date }}
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []

output:
  blogdown::html_page:
    toc: true
    number_sections: true
    toc_depth: 1
---
