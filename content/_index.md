---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
  #   design:
  #     columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Software Engineer
          company: Amazon
          company_url: ''
          company_logo: amazon
          location: Seattle, WA
          date_start: '2019-06-01'
          date_end: '2019-08-31'
          description: Designed an internal tool for bug detection and reporting.
        - title: Intern
          company: JHU Applied Physics Lab, NASA
          company_url: ''
          company_logo: nasa
          location: Laurel, MD
          date_start: '2018-06-01'
          date_end: '2018-08-31'
          description: Developed an algorithm for scene reconstruction from Lidar, automated landing zone selection, and minimum fuel-cost trajectories for the Dragonfly project.
        - title: Software Engineering Intern
          company: Mathworks
          company_url: ''
          company_logo: matlab
          location: Natick MA
          date_start: '2017-06-01'
          date_end: '2017-08-31'
          description: Created an algorithm for real-time data compression, optimised data structures for MATLAB speed increases, and formulated an approach for Simulink anomaly detection using a graph fourier transform.
    design:
      columns: '2'
  - block: experience
    content:
      title: 'Education'
      subtitle:
      date_format: Jan 2006
      items:
        - title: University of Cambridge
          company: |2- 
            PhD in Computer Science
          company_url: ''
          company_logo: cambridge
          location: Cambridge, UK
          date_start: '2019-10-01'
          date_end: '2024-02-13'
          description: |2-
            - *Graph Neural Networks for Multi-Agent Learning*
            - *Supervisor: Amanda Prorok*
            - *Prorok Lab*
        - title: University of Pennsylvania
          company: BSE in Electrical Engineering
          company_url: ''
          company_logo: upenn
          location: Philadelphia, PA
          date_start: '2016-09-01'
          date_end: '2019-05-31'
          description: |2-
            - *Minors in Computer Science and Mathematics*
            - *Graduated summa cum laude*
    design:
      columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        [All Publications](./publication/)
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: collection
    id: posts
    content:
      title: Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: collection
    id: talks
    content:
      title: Talks & Teaching
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: #|-
        # Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: rk627@cam.ac.uk
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: 15 JJ Thomson Ave
        city: Cambridge
        region: Cambridgeshire
        postcode: 'CB3 0FD'
        country: United Kingdom
        country_code: UK
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '52.21125657062588'
      #   longitude: '0.09202243562305723'  
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
