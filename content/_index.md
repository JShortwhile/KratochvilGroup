---
title: Our STEM Research Lab
date: 2026-10-15
type: landing
summary: "Welcome to our STEM research group website. Discover our team, equipment, projects, publications, news, and contact information."

design:
  spacing: "6rem"

sections:
  - block: hero
    id: intro
    content:
      title: "Welcome to the **Future** of **STEM Research**"
      eyebrow: STEM Research Group
      text: We are a multidisciplinary research group focused on pioneering solutions in science and technology.
      primary_action:
        text: Meet the Team
        url: "#team"
        icon: hero/users
      secondary_action:
        text: Latest Projects
        url: "#projects"
        icon: hero/bolt
    design:
      css_class: relative overflow-hidden
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
      background:
        text_color_light: true
        image:
          filename: hero-lab.jpg
          size: cover
          position: center
          parallax: true
        gradient:
          start: primary-500
          end: transparent
          type: radial

  - block: features
    id: team
    content:
      title: Our Dedicated Team
      text: Meet the talented scientists and staff who drive our lab forward.
      items:
        - name: Dr. Alice Smith
          description: "**Principal Investigator** — Expert in molecular biology and bioinformatics."
          icon: hero/academic-cap
        - name: Dr. Bob Johnson
          description: "**Postdoctoral Researcher** — Specializes in nanomaterials and device physics."
          icon: hero/beaker
        - name: Carla Martinez
          description: "**PhD Candidate** — Working on computational modeling of complex systems."
          icon: hero/cpu-chip
    design:
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
      background:
        color: primary-50

  - block: features
    id: equipment
    content:
      title: State-of-the-Art Equipment
      text: A closer look at the cutting-edge tools powering our discoveries.
      items:
        - name: High-Resolution Microscope
          description: Enables atomic-level imaging with ultra-precision.
          icon: hero/magnifying-glass-plus
        - name: Supercomputer Cluster
          description: Handles large-scale simulations and data processing.
          icon: hero/server
        - name: 3D Bioprinter
          description: Fabricates complex biological structures with high accuracy.
          icon: hero/printer
    design:
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
      background:
        color: primary-100

  - block: collection
    id: projects
    content:
      title: Our Research Projects
      text: Explore the diverse research projects underway in our lab.
      count: 4
      sort_by: date
      sort_ascending: false
      filters:
        folders:
          - project
    design:
      view: card
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
      background:
        color: primary-50

  - block: collection
    id: publications
    content:
      title: Publications
      text: Recent papers and articles published by our group.
      count: 5
      sort_by: date
      sort_ascending: false
      filters:
        folders:
          - publication
    design:
      view: citation
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
      background:
        color: primary-100

  - block: collection
    id: news
    content:
      title: "News & Events"
      text: Stay updated on our latest announcements and upcoming events.
      count: 3
      sort_by: date
      sort_ascending: false
      filters:
        folders:
          - post
    design:
      view: compact
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
      background:
        color: primary-50

  - block: markdown
    id: contact
    content:
      title: Get in Touch
      subtitle: "Contact us for collaboration, questions, or visits."
      text: |
        - **Email:** [contact@stemlab.edu](mailto:contact@stemlab.edu)
        - **Phone:** +123-456-7890
        - **Address:** 123 Science Ave, Research City, Country
        - **Connect:** [Twitter](https://twitter.com/ourstemlab) | [LinkedIn](https://linkedin.com/company/ourstemlab)
    design:
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
      background:
        color: primary-100
---
