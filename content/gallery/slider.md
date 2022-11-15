---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to the group
      content: ...getting sunburnt on our terrace
      align: center
      background:
        position: center
        brightness: 1
        media: gallery/terrazza02.jpg
        fit: cover
    - title: Our home
      content: 'East Campus at Università della Svizzera Italiana (USI)'
      align: left
      background:
        position: center
        brightness: 1
        fit: cover
        media: gallery/campus-est-gp-plogger-16-1.jpg
      link:
        icon: home
        icon_pack: fas
        text: USI
        url: 'https://www.usi.ch'
    - title: Internship opportunities
      content: 'Work with us for your bachelor & master thesis'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.8
        fit: cover
        media: gallery/lab01.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../openings/
    - title: Alternative research
      align: left
      background:
        position: center
        color: '#4373a0'
        brightness: 1
        fit: cover
        media: gallery/pizza02.jpeg
    
---
