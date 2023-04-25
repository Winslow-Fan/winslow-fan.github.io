---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 90%
          icon: python
          icon_pack: fab
        - name: Statistics
          description: 90%
          icon: chart-line
          icon_pack: fas
        - name: MATLAB
          description: 10%
          icon: calculator
          icon_pack: fas
  - block: experience
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
        - title: Research Fellow
          company: HITCQ
          company_url: ''
          company_logo: building-columns-solid
          location: Chongqing, CN
          date_start: '2022-11-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Deep Learning Algorithms
              * Modelling
              * Indeustrial Anomaly Detection
        - title: MSc
          company: The University of Sheffield
          company_url: ''
          company_logo: building-columns-solid
          location: Sheffield, UK
          date_start: '2021-09-27'
          date_end: '2022-09-27'
          description: Majoring in Robotics. Getting trained in intelligient robots designing and deep learning algorithms.
        - title: BSc
          company: Beijing Institute of Technology
          company_url: ''
          company_logo: building-columns-solid
          location: Beijing, CN
          date_start: '2017-08-27'
          date_end: '2021-07-02'
          description: Majoring in Aerospace Engineering. Focusing on intelligient aerial robotics and automatic control.
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
        # - certificate_url: https://www.coursera.org
        #   date_end: ''
        #   date_start: '2021-01-25'
        #   description: ''
        #   organization: Coursera
        #   organization_url: https://www.coursera.org
        #   title: Neural Networks and Deep Learning
        #   url: ''
        # - certificate_url: https://www.edx.org
        #   date_end: ''
        #   date_start: '2021-01-01'
        #   description: Formulated informed blockchain models, hypotheses, and use cases.
        #   organization: edX
        #   organization_url: https://www.edx.org
        #   title: Blockchain Fundamentals
        #   url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        # - certificate_url: https://www.datacamp.com
        #   date_end: '2020-12-21'
        #   date_start: '2020-07-01'
        #   description: ''
        #   organization: DataCamp
        #   organization_url: https://www.datacamp.com
        #   title: 'Object-Oriented Programming in R'
        #   url: ''
    # design:
    #   columns: '2'

    # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: collection
    content:
      title: Recent Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: posts
    content:
      title: Recent Posts
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

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
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
      # text: |-
      #   Please leave your contact information and message, I'll contact you as soon as possible.
      # Contact (add or remove contact options as necessary)
      email: winslowfan0317@gmail.com
      # phone: +86-16619996928
      # appointment_url: 'https://calendly.com'
      address:
        street: HITCQ, Mingyue Lake, Collaboration Innovation Zone
        city: Chongqing
        region: Chongqing
        postcode: '401135'
        country: China
        country_code: CN
      directions: Enter Building 14 and take the stairs to Office 409 on Floor 4
      office_hours:
        - 'Monday~Friday 09:00 to 18:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/WinslowFan0317'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
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
  # - block: links
  #   id: links
  #   content: 
  #     title: Friends & Collaborators

---
