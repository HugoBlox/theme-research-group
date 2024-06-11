---
# Leave the homepage title empty to use the site title
title: 
type: landing


sections:
  - block: hero
    content:
      title: |
        APEX Lab
      image:
        filename: sfu.jpg
      text: |
        <br>
        
        The **APEX lab** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  - block: slider
    content:
      slides:
      - title: 
        content: ''
        align: center
        background:
          image:
            filename: slide/gp1.jpg
            filters:
              brightness: 0.8
          position: center
          color: '#333'
      - title: Join the APEX Lab
        content: ''
        align: center
        background:
          position: center
          color: '#333'
          image:
            filename: slide/sfu.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '500px'
      is_fullscreen: False
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000
  
  
  - block: collection
    content:
      title: Latest Publications
      subtitle:
      text: 
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: card
      columns: '2'

  - block: collection
    content:
      title: Latest Posts
      subtitle:
      text:
      count: 1
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
      view: card
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'
