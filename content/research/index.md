---
title: Research
date: 2023-12-16
type: landing

sections:
  # - block: hero
  #   content:
  #     title: |
  #       Wowchemy
  #       Research Group
  #     image:
  #       filename: welcome.jpg
  #     text: |
  #       <br>
        
  #       The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  # - block: collection
  #   content:
  #     title: Research Highlights
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: highlights
  #   design:
  #     view: compact
  #     columns: '1'
  
  - block: markdown
    content:
      title: Brain-Machine Fusion
      subtitle: From brain-in-the-loop to brain-out-of-the-loop
      text: abstract here
      url: ../highlights/
    design:
      columns: '1'
      background:
        image: 
          filename: AI_Eye.jpg
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
      title: Brain-Machine Fusion
      subtitle: From brain-in-the-loop to brain-out-of-the-loop
      text: |
        {{% cta cta_link="./highlights-fusion.html" cta_text="Research Highlights →" %}}
    design:
      columns: '1'
---