---
title: Our STEM Research Lab
date: 2026-10-15
design:
  spacing: 6rem
summary: "Welcome to our STEM research group website. Discover our team, equipment, projects, publications, news, and contact information."
type: landing
sections:
  - id: intro
    block: hero
    design:
      image:
        size: cover
        filename: hero-lab.jpg
        parallax: true
        position: center
      background:
        gradient:
          end: transparent
          size: "80% 80%"
          type: radial
          shape: ellipse
          start: primary-500
          position: center
      text_color_light: true
    content:
      text: We are a multidisciplinary research group focused on pioneering solutions in science and technology.
      title: "Welcome to the [Future] of [STEM Research]"
      eyebrow: STEM Research Group
      primary_action:
        url: "#team"
        icon: hero/users
        text: Meet the Team
        style: gradient
      secondary_action:
        url: "#projects"
        icon: hero/lightning-bolt
        text: Latest Projects
        style: ghost
    spacing:
      padding:
        - 4rem
        - 0
        - 4rem
        - 0
    css_class: relative overflow-hidden
  - id: team
    block: team-showcase
    design:
      spacing:
        padding:
          - 4rem
          - 0
          - 4rem
          - 0
      background:
        color: primary-50
    content:
      text: Meet the talented scientists and staff who drive our lab forward.
      title: Our Dedicated Team
      members:
        - bio: Expert in molecular biology and bioinformatics.
          name: Dr. Alice Smith
          role: Principal Investigator
          image: team-alice.jpg
          social:
            - url: "https://orcid.org/0000-0001-2345-6789"
              network: orcid
        - bio: Specializes in nanomaterials and device physics.
          name: Dr. Bob Johnson
          role: Postdoctoral Researcher
          image: team-bob.jpg
          social:
            - url: "https://linkedin.com/in/bobjohnson"
              network: linkedin
        - bio: Working on computational modeling of complex systems.
          name: Carla Martinez
          role: PhD Candidate
          image: team-carla.jpg
          social: []
  - id: equipment
    block: features
    design:
      layout: grid
      spacing:
        padding:
          - 4rem
          - 0
          - 4rem
          - 0
      background:
        color: primary-100
    content:
      text: A closer look at the cutting-edge tools powering our discoveries.
      items:
        - icon: hero/microscope
          name: High-Resolution Microscope
          description: Enables atomic-level imaging with ultra-precision.
        - icon: hero/server
          name: Supercomputer Cluster
          description: Handles large-scale simulations and data processing.
        - icon: hero/printer
          name: 3D Bioprinter
          description: Fabricates complex biological structures with high accuracy.
      title: State-of-the-Art Equipment
  - id: projects
    block: collection
    design:
      view: card
      spacing:
        padding:
          - 4rem
          - 0
          - 4rem
          - 0
      background:
        color: primary-50
    content:
      text: Explore the diverse research projects underway in our lab.
      count: 4
      title: Our Research Projects
      sort_by: date
      page_type: project
      sort_ascending: false
  - id: publications
    block: collection
    design:
      view: citation
      spacing:
        padding:
          - 4rem
          - 0
          - 4rem
          - 0
      background:
        color: primary-100
    content:
      text: Recent papers and articles published by our group.
      count: 5
      title: Publications
      sort_by: date
      page_type: publication
      sort_ascending: false
  - id: news
    block: collection
    design:
      view: compact
      spacing:
        padding:
          - 4rem
          - 0
          - 4rem
          - 0
      background:
        color: primary-50
    content:
      text: Stay updated on our latest announcements and upcoming events.
      count: 3
      title: "News & Events"
      sort_by: date
      page_type: post
      sort_ascending: false
  - id: contact
    block: contact-info
    design:
      spacing:
        padding:
          - 4rem
          - 0
          - 4rem
          - 0
      background:
        color: primary-100
    content:
      text: "Contact us for collaboration, questions, or visits."
      email: "contact@stemlab.edu"
      phone: +123-456-7890
      title: Get in Touch
      address: "123 Science Ave, Research City, Country"
      social_links:
        - url: "https://twitter.com/ourstemlab"
          network: twitter
        - url: "https://linkedin.com/company/ourstemlab"
          network: linkedin
---
