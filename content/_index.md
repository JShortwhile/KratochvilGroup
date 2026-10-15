---
title: Our STEM Research Lab
date: 2026-10-15
summary: "Welcome to our STEM research group website. Discover our team, equipment, projects, publications, news, and contact information."
design:
  spacing: 6rem
type: landing
sections:
  - block: hero
    content:
        eyebrow: STEM Research Group
        title: "Welcome to the [Future] of [STEM Research]"
        text: We are a multidisciplinary research group focused on pioneering solutions in science and technology.
        primary_action:
          text: Meet the Team
          url: "#team"
          icon: hero/users
          style: gradient
        secondary_action:
          text: Latest Projects
          url: "#projects"
          icon: hero/lightning-bolt
          style: ghost
    design:
        background:
          gradient:
            type: radial
            start: primary-500
            end: transparent
            position: center
            shape: ellipse
            size: "80% 80%"
        text_color_light: true
        image:
          filename: hero-lab.jpg
          size: cover
          position: center
          parallax: true
    id: intro
    spacing:
        padding:
          - 4rem
          - 0
          - 4rem
          - 0
    css_class: relative overflow-hidden
  - block: team-showcase
    content:
        title: Our Dedicated Team
        text: Meet the talented scientists and staff who drive our lab forward.
        members:
          - name: Dr. Alice Smith
            role: Principal Investigator
            image: team-alice.jpg
            bio: Expert in molecular biology and bioinformatics.
            social:
                - network: orcid
                  url: "https://orcid.org/0000-0001-2345-6789"
          - name: Dr. Bob Johnson
            role: Postdoctoral Researcher
            image: team-bob.jpg
            bio: Specializes in nanomaterials and device physics.
            social:
                - network: linkedin
                  url: "https://linkedin.com/in/bobjohnson"
          - name: Carla Martinez
            role: PhD Candidate
            image: team-carla.jpg
            bio: Working on computational modeling of complex systems.
            social: []
    design:
        background:
          color: primary-50
        spacing:
          padding:
            - 4rem
            - 0
            - 4rem
            - 0
    id: team
  - block: features
    content:
        title: State-of-the-Art Equipment
        text: A closer look at the cutting-edge tools powering our discoveries.
        items:
          - name: High-Resolution Microscope
            description: Enables atomic-level imaging with ultra-precision.
            icon: hero/microscope
          - name: Supercomputer Cluster
            description: Handles large-scale simulations and data processing.
            icon: hero/server
          - name: 3D Bioprinter
            description: Fabricates complex biological structures with high accuracy.
            icon: hero/printer
    design:
        background:
          color: primary-100
        layout: grid
        spacing:
          padding:
            - 4rem
            - 0
            - 4rem
            - 0
    id: equipment
  - block: collection
    content:
        title: Our Research Projects
        text: Explore the diverse research projects underway in our lab.
        count: 4
        page_type: project
        sort_by: date
        sort_ascending: false
    design:
        background:
          color: primary-50
        spacing:
          padding:
            - 4rem
            - 0
            - 4rem
            - 0
        view: card
    id: projects
  - block: collection
    content:
        title: Publications
        text: Recent papers and articles published by our group.
        count: 5
        page_type: publication
        sort_by: date
        sort_ascending: false
    design:
        background:
          color: primary-100
        spacing:
          padding:
            - 4rem
            - 0
            - 4rem
            - 0
        view: citation
    id: publications
  - block: collection
    content:
        title: "News & Events"
        text: Stay updated on our latest announcements and upcoming events.
        count: 3
        page_type: post
        sort_by: date
        sort_ascending: false
    design:
        background:
          color: primary-50
        spacing:
          padding:
            - 4rem
            - 0
            - 4rem
            - 0
        view: compact
    id: news
  - block: contact-info
    content:
        title: Get in Touch
        text: "Contact us for collaboration, questions, or visits."
        address: "123 Science Ave, Research City, Country"
        email: "contact@stemlab.edu"
        phone: +123-456-7890
        social_links:
          - network: twitter
            url: "https://twitter.com/ourstemlab"
          - network: linkedin
            url: "https://linkedin.com/company/ourstemlab"
    design:
        background:
          color: primary-100
        spacing:
          padding:
            - 4rem
            - 0
            - 4rem
            - 0
    id: contact
---
