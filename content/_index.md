---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to TExUs group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: maincampus_hero.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Extreme Weather & Urban Sustainability ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: maincampus_yellow.jpeg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Data for urbanization and climate change
        content: ''
        align: right
        background:
          image:
            filename: IMG_8784.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  # - block: hero
  #   content:
  #     title: |
  #       Texas Extreme Weather & Urban Sustainability 
  #       Research Group
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
        
  #       The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
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
      view: card
      columns: '1'
      
  - block: portfolio
    id: researches
    content:
      title: Research Projects
      filters:
        folders:
          - researches
        kinds:
          - page
      sort_by: 'Date'
      sort_ascending: false
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Reinforcement Learning
          tag: Reinforcement Learning
        - name: IAQ
          tag: IAQ
        - name: Other
          tag: Other
      design:
        columns: '2'
        view: masonry
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       <br>
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   link:
  #     icon: graduation-cap
  #     icon_pack: fas
  #     text: Join Us
  #     url: ../contact/
  #   design:
  #     columns: '1'
---

