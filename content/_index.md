---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Tree growth depends not only on carbon gain but also on how carbon is allocated to build and maintain the canopy. 
        The three-dimensional arrangement of stems, branches and foliage shapes canopy architecture, 
        influencing how trees occupy space, intercept light, acquire resources, and interact with their environment.
        
        I am interested in why trees build different canopy architectures, how these structures shape individual tree performance, 
        and how their effects scale up to influence forest communities and ecosystem functioning.

        **Plant Strategies and Crown Architecture**
        How do plant functional strategies and environmental conditioins shape tree crown architecture?

        We are using terrestrial laser scanning (TLS) and individual-tree reconstruction in coastal mangrove forests 
        to investigate differences in canopy architecture among trees with contrasting resource-use strategies.
        The ongoing work aims to reveal how variation in plant strategies is reflected in the three-dimensional organization of tree canopies.

        **Crown Architecture and Tree Performance**
        How does crown architecture shape resource acquisition, tree growth, and survival?

        Addressing this question requires linking three-dimensional canopy structure with field measurements of tree performance.
        By integrating TLS-based reconstructions with field observations and ecological modeling, 
        I aim to investigate how architectural variation translates into differences in resource acquisition,
        growth, and ultimately tree performance.

        **Crown Architecture and Ecosystem Functioning**
        How do tree crown architectures influence forest regeneration, community dynamics, and ecosystem productivity?

        We have initiated a preliminary study examining how species combination relates to ecosystem resistance and resilience 
        following cyclone disturbance in mangrove forests. 
        Building on this work, I aim to investigate how species interactions and variation in tree architecture jointly shape
        community dynamics and ecosystem responses to environmental disturbances.


        **What I bring**
        - Long-term ecological datasets, including litterfall records and seedling experiments.
        - Terrestrial laser scanning, hyperspectral modelling, and satellite remote sensing.
        - Statistical modelling, including Bayesian structural equation modeling and machine learning.
        - Global data synthesis and meta-analysis.


        **What I am looking for**
        I am seeking a research position starting March 2027. 
        I would welcome opportunities to join research groups working on blue carbon, plant functional traits, forest resilience, or vegetation remote sensing, 
        and I am open to collaborations that extend beyond these areas. 
        
        If my research interests align with yours, Please [get in touch](mailto:huangzj79@mail.sysu.edu.cn).
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 1
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: blog
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 10
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the HugoBlox Kit demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by HugoBlox Kit - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/kit" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/kit on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!

  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: 'bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl'
  #       css_style: ''
---
