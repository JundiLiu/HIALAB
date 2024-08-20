---
title: Lab
type: landing

sections:
  - block: markdown
    content:
      title: 👋 Welcome to the HIA Lab
      subtitle:  
      text: "Human-centered Interactive Autonomy (HIA) Lab leverages Human Factors research techniques,  human-in-the-loop reinforcement learning and trustworthy machine learning algorithms to design human-centered and trust-aware customized autonomy. We aim to answer two fundamental questions:
      
      1. **Can we model human cognition and behavior formally and holistically?**  
      

       > Humans constantly provide implicit and hidden feedback while interacting with autonomous systems. It is crucial to leverage the multimodal human sensory data to formally define models that are generalizable and personalized.
      

       2. **Can we integrate humans in the loop?**
      
      
        > To build customized AI systems as trustworthy teammates to better collaborate with human users in complex decision-making tasks, we aim to integrate humans in the framework to achieve transparent and responsive interaction without interrupting or intruding."
      

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: slider
    content:
      slides:
        - title: Virtual Reality Apparatus
          content: for Human-Robot Interaction Research
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: VR_apparatus.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: Driving Simulator
          content: for Connected Vehicles and Human-Vehicle Interaction
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: driving_sim.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        # - title: World-Class Semiconductor Lab
        #   content: 'Just opened last month!'
        #   align: right
        #   background:
        #     image:
        #       # Specify an image from `assets/media/`
        #       # or delete the image section to remove it
        #       filename: welcome.jpg
        #       filters:
        #         brightness: 0.5
        #     position: center
        #     color: '#333'
        #   link:
        #     icon: graduation-cap
        #     icon_pack: fas
        #     text: Join Us
        #     url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '800px'
      # Make the slides full screen within the browser window?
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="../people/" cta_text="Lab members →" %}} 
        {{% cta cta_link="../publication/" cta_text="Publications →" %}}
    design:
      columns: '1'
---
