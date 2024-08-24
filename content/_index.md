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
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
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
        - title: Research Assistant
          company: Istanbul Technical University
          company_url: ''
          company_logo: itu
          location: Türkiye
          date_start: '2020-02-17'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Research on satellite geodesy, and GNSS reflectometry.
              * Teaching/assisting lectures on computer programming and geodesy.
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     date_format: Jan 2006
  #     items:
  #       - certificate_url: 
  #         date_end: ''
  #         date_start: ''
  #         description: ''
  #         icon: 
  #         organization: 
  #         organization_url: 
  #         title: 
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
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
  - block: markdown
    id: gallery1
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Journal Papers
      count: 0
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
        publication_type: "article-journal"
    design:
      columns: '2'
      view: citation
  - block: collection
    content:
      title: Conference Papers
      count: 0
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
        publication_type: "paper-conference"
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: mutlubil@itu.edu.tr
    #  phone: 888 888 88 88
    #  appointment_url: 'https://calendly.com'
      address:
        street: İstanbul Teknik Üniversitesi, Ayazağa Kampüsü, İnşaat Fakültesi, Geomatik Mühendisliği Bölümü, Ofis No:G303, 34469 Sarıyer
        city: İstanbul
      #  region: 
      #  postcode: '34469'
      #  country: United States
      #  country_code: US
      directions: ITU Faculty of Civil Engineering, Department of Geomatics Engineering, Office No:G303, Maslak, Istanbul
      #office_hours:
      #  - 'Monday 10:00 to 12:00'
      #  - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude:  '41.104558'
        longitude: '29.019420'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/sakalface'
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree: "https://formspree.io/f/mblrppkj"
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
