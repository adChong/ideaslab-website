---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        IDEASLab @ NUS
      text: |
        Advancing Research at the Intersection of Sustainable Cooling, Thermal Comfort, and Occupant-Centric Controls
    design:
      columns: '1'
      background:
        image:
          filename: sde4-night.png
          position: center
          size: cover
        color: 'black'
        spacing:
          padding: ['20px', '0', '20px', '0']
        text_color_light: true
      css_class: fullscreen



  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'
  



  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
