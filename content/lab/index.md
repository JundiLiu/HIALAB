---
title: My page
type: landing

sections:
  - block: markdown
    content:
      title: 👋 Welcome to the HIA Lab
      subtitle: 
      text: "Human-centered Interactive Autonomy (HIA) Lab leverages Human Factors research techniques,  human-in-the-loop reinforcement learning and trustworthy machine learning algorithms to design human-centered and trust-aware customized autonomy. We aim to answer two fundamental questions:
      
      1. **Can we model human cognition and behavior formally and holistically?**  
      

      > Human constantly provides implicit and hidden feedback while interacting with autonomous systems. It is crucial to leverage the multimodal human sensory data to formally define models that are generalizable and personalized.
      

      2. **Can we integrate human in the loop?**
      
      
      > To build customized AI systems as trustworthy teammates to better collaborate with human users in complex decision-making tasks, we aim to integrate human in the framework to achieve transparent and responsive interaction without interrupting or intruding."
      

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: slider
    content:
      slides:
        - title: 👋 Welcome to the group
          content: Take a look at what we're working on...
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: coders.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: Lunch & Learn ☕️
          content: 'Share your knowledge with the group and explore exciting new topics together!'
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: contact.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: World-Class Semiconductor Lab
          content: 'Just opened last month!'
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: welcome.jpg
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
      slide_height: '500px'
      # Make the slides full screen within the browser window?
      is_fullscreen: false
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Lab members →" %}} 
        {{% cta cta_link="./projects/" cta_text="Projects →" %}}
    design:
      columns: '1'
---
