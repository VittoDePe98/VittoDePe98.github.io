---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |-
        Italian-Brazilian PhD student at KAUST and Doctoral Researcher with the DeepWave Consortium, building machine- and deep-learning workflows for subsurface reservoir characterization. I focus on deep generative AI, especially video diffusion models, to model multi-phase subsurface fluid-flow dynamics. My workflows rely on CUDA-aware, reproducible CPU/GPU pipelines running at scale on the KAUST IBEX Supercomputing cluster.
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_Vittoria_De_Pellegrini_2025.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a custom layered background
      css_style: "background-image: linear-gradient(135deg, rgba(7, 33, 53, 0.9), rgba(2, 17, 23, 0.75)), url('/assets/media/background.png'); background-size: cover; background-position: center; background-repeat: no-repeat; border-radius: 2px;"
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: collection
    id: conference-publications
    content:
      title: Conference Publications
      text: 'Peer-reviewed submissions where I present diffusion modeling for CO₂ workflows.'
      filters:
        folders:
          - conference-paper
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: paper-publications
    content:
      title: Paper Publications
      text: 'In-depth technical papers and proceedings that capture the experiments behind DeepWave.'
      filters:
        folders:
          - paper-publication
    design:
      view: citation
      columns: 1
  - block: collection
    id: thesis
    content:
      title: Thesis
      text: 'My Master’s thesis exploring supervised machine learning for well-log prediction.'
      filters:
        folders:
          - thesis
    design:
      view: card
  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: false
  - block: collection
    id: projects
    content:
      title: Projects
      text: 'Featured work and collaborations.'
      filters:
        folders:
          - projects
    design:
      view: card
      columns: 2
---
