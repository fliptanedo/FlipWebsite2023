---
widget: slider
weight: 30
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  # FLIP: This is a hack to put more CSS into the bg image
  slide_height: '300px; background-position:center; background-repeat: no-repeat; background-size: cover'
  # Turn off full screen if using specified height
  is_fullscreen: false 
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 3500

content:
  slides:
    - title: 
      content: Find my papers on InspireHEP
      align: center
      background:
        position: right
        # color: '#666'
        brightness: 0.7
        media: research/carousel_chalkboard.jpg
      link:
        icon: atom
        icon_pack: fas
        text: Join Us
        url: https://inspirehep.net/authors/1049892
    # 
    - title: ML
      content: Machine Learning High-Dimensional Theory Spaces
      align: left
      background:
        position: left
        # color: '#666'
        brightness: 0.7
        media: research/carousel_ml.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: 2103.06957
        url: https://arxiv.org/abs/2103.06957
      credit: '[@fabioha via Unsplash](https://unsplash.com/photos/oyXis2kALVg)'
    #
    - title: Dark Z
      content: at linear colliders
      align: right
      background:
        position: left
        # color: '#666'
        brightness: 0.7
        media: research/carousel_ILC.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: 2205.10304
        url: https://arxiv.org/abs/2205.10304
      credit: '[@Umberto via Unsplash](https://unsplash.com/photos/FewHpO4VC9Y)'
    #
    - title: Conformal DM
      content: Continuum Mediated Self-Interactions
      align: left
      background:
        position: left
        # color: '#666'
        brightness: 0.7
        media: research/carousel_sidm.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: 2102.05674
        url: https://arxiv.org/abs/2102.05674
      credit: '[Adrien Olichon via Pexels](https://www.pexels.com/photo/black-sand-dunes-2387793/)'
    #
    - title: AdS
      content: Continuum Soft Bombs
      align: left
      background:
        position: left
        # color: '#666'
        brightness: 0.7
        media: research/carousel_softbomb.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: 2002.12335
        url: https://arxiv.org/abs/2002.12335
      credit: '[Jessica Lewis via Pexels](https://www.pexels.com/photo/close-up-photo-of-dandelion-1118427/)'
    #
    - title: DM Capture
      content: on relativistic targets
      align: right
      background:
        position: left
        # color: '#666'
        brightness: 0.7
        media: research/carousel_neutronstar.png  # path relative to `assets/
      link:
        icon: graduation-cap
        icon_pack: fas
        text: 2004.09539
        url: https://arxiv.org/abs/2004.09539
      credit: '[FNS via Pexels](https://www.pexels.com/photo/stars-during-nighttime-127577/)'
    #
    - title: Symmetry Breaking
      content: vector self-interacting dark matter
      align: left
      background:
        position: left
        # color: '#666'
        brightness: 0.7
        media: research/carousel_fiberbundle.jpg  # path relative to `assets/
      link:
        icon: graduation-cap
        icon_pack: fas
        text: 1907.10217
        url: https://arxiv.org/abs/1907.10217
      credit: '[@anyctophile via Unsplash ("fiber bundle" 😄)](https://unsplash.com/photos/8uTqI_KpC_Q)'
    #
    # - title: Lunch & Learn ☕️
    #   content: 'Share your knowledge with the group and explore exciting new topics together!'
    #   align: left
    #   background:
    #     position: center
    #     color: '#555'
    #     brightness: 0.7
    #     media: contact.jpg
    # - title: World-Class Semiconductor Lab
    #   content: 'Just opened last month!'
    #   align: right
    #   background:
    #     position: center
    #     color: '#333'
    #     brightness: 0.5
    #     media: welcome.jpg
    #   link:
    #     icon: graduation-cap
    #     icon_pack: fas
    #     text: Join Us
    #     url: ../contact/
---