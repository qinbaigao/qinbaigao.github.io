---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: About
        education: Education
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
      sort_by: Weight
      sort_ascending: true
    design:
      view: publication-detail
      show_date: false
      show_read_time: false
---
