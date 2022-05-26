---
widget: slider  # Use the Slider widget as this page section
weight: 2  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to the group 
      content: World leading group in biomedical imaging...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: HomeCover_4.png
    - title: Lunch & Learn ☕️
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: HomeCover_6.png
    - title: World-Class Optics Lab
      content: 'Solve world-class challenge in biomedical imaging!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.9
        media: HomeCover_9.png
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
