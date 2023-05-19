---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: featured
    content:
      title: Featured Projects
      page_type: publication
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      # view: card
      view: compact
  - block: collection
    id: recent_pub
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      count: 0
      offset: 0
      order: desc
    design:
      columns: '2'
      view: citation
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      # title: 'Accomplish&shy;ments'
      title: 'News'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Best Paper Award
          date_start: '2022-05-20'
          description: 'Our paper "FPGA Acceleration of Deep Reinforcement Learning using On-Chip Replay Management" received Best Paper Award in the 2022 ACM International Conference on Computing Frontiers!'
          organization: 2022 ACM/CF
          organization_url: https://www.computingfrontiers.org/2022/
          url: https://drive.google.com/file/d/1GOy_ehtrjD5hzoOI2Pr-hoSv7vl1zeUA/view
        - title: Outstanding Student Paper Award
          date_start: '2020-10-16'
          description: 'Our paper "How to efficiently train your ai agent? characterizing and evaluating deep reinforcement learning on heterogeneous platforms" received Outstanding Student Paper Award in the 2020 IEEE High Performance Extreme Computing Virtual Conference!'
          organization: 2020 IEEE/HPEC
          organization_url: https://ieee-hpec.org/2020/
          url: https://drive.google.com/file/d/13DJXKtB1pHR6HlCx6_aBl-1i7c55esiQ/view
        # - title: Academic Service
        #   date_start: '2022-10-01'
        #   description: 'I am serving as the Proceedings Chair for HiPC 2022'
        #   organization: 2022 IEEE/HiPC
        #   organization_url: https://hipc.org/
        - title: Scholarship Nomination
          date_start: '2022-09-30'
          description: 'I am selected as one of the finalists of the Ming Hsieh Ph.D. Scholar!'
          organization: Department of Electrical and Computer Engineering, USC
          # organization_url: https://hipc.org/
        # - title: Academic Service
        #   date_start: '2023-03-01'
        #   description: 'I am serving as the Publications Chair for FCCM 2023'
        #   organization: 2023 IEEE/FCCM
        #   organization_url: https://www.fccm.org/

    design:
      columns: '2'
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Teaching Assistant
          company: University of Southern California
          company_url: ''
          company_logo: usc
          location: California
          date_start: '2020-01-01'
          date_end: '2021-12-03'
          description: |2-
              Taught courses:

              * Parallel and Distributed Computing
              * Accelerated Computing using FPGAs
              * Parallel Programming
        - title: Undergraduate Teaching Assistant
          company: Rensselaer Polytechnic Institute
          company_url: ''
          company_logo: rpi
          location: California
          date_start: '2017-01-01'
          date_end: '2019-01-01'
          description: |2-
              Taught courses:

              * Embedded Control
              * Foundation of Computer Science
        - title: Electronics Engineer (Intern)
          company: Hasbro. Inc
          company_url: ''
          company_logo: Hasbro
          location: California
          date_start: '2018-01-01'
          date_end: '2018-06-20'
          description: |2-
              Prototyping for Animatronics and games;

              Research on embedded voice recognition and computer vision applications in toys.
    design:
      columns: '2'
  - block: features
    content:
      title: Skills
      items:
        - name: Parallel Programming
          description: P-Threads, OpenMP, MPI, SYCL
          icon: sidebar
          icon_pack: fab
        - name: Hardware Design
          description: High-Level Synthesis
          icon: gear-code
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: ymeng643@usc.edu
      # phone: 518 961 3768
      # appointment_url: 'https://calendly.com'
      address:
        street: 3740 McClintock Ave
        city: Los Angeles
        region: CA
        postcode: '90089'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
{{% callout note %}}
Quickly discover relevant content by [filtering publications](./publication/).
{{% /callout %}}