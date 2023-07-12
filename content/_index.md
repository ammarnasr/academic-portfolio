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
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 90%
          icon: python
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
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
        - title: Teaching Assistant
          company: School of Informatics, The University of Edinburgh
          company_url: 'https://www.ed.ac.uk/informatics'
          company_logo: edinburgh
          location: Edinburgh, UK
          date_start: '2023-01-01'
          date_end: ''
          description: |2-
              * Worked as TA with Dr. Amir Vaxman for the Computer Graphics Course which introduces classic and state-of-the-art methodology in computer graphics.
              * I was responsible for the coursework in which we designed three programming exercises -a skeleton code and an automatic self-checker- each covering a single major algorithm learned in class.
        - title: Data Scientist
          company: AmunData, Data-Driven Research, and Advisory
          company_url: 'https://twitter.com/AmunData_'
          company_logo: amundata
          location: Khartoum, Sudan
          date_start: '2022-01-01'
          date_end: '2022-09-01'
          description: |2-
              * Designing and implementing services primarily focused on precision agriculture using remote sensing data.
              * Modelling and analyzing time-series satellite data as well as field measurements to provide our clients with real-time crop monitoring
              * Deploying and maintaining a web application that analyzes time-series satellite data as well as field measurements to provide our clients with real-time crop monitoring
        - title: Research Assistant
          company: University College Dublin
          company_url: 'https://www.ucd.ie/'
          company_logo: ucd
          location: Dublin, Ireland
          date_start: '2022-03-01'
          date_end: '2022-08-01'
          description: |2-
              * Worked with DR Mohamed Saadeldin -Assistant Professor in School of Computer Science, UCD- on a project about multi-label image classification.
              * Evaluated and compared performance of neural networks with conventional output layer against neural networks utilizing the Kasami Orthogonal Classification Layer (KOCL) in the task of multi-label image classification
              * Our work extended neural networks trained on single class data to provide classification output for multi-label data without further training. The results were presented in the NLDL2022 conference
        - title: Backend Developer
          company: KooshLyncs For Software Solutions
          company_url: ''
          company_logo: 
          location: Khartoum, Sudan
          date_start: '2021-07-01'
          date_end: '2021-12-01'
          description: |2-
              * Worked in the fin-tech sector to develop an online marketplace for Sudan.
              * Designed the company’s back-end microservices for data storage, authentication and third-party integration. The services were implemented in GoLang and hosted on AWS Elastic Beans to ensure performance and scalability
        - title: Full Stack Developer
          company: Code Software Sudan
          company_url: 'https://code.sd/'
          company_logo: code
          location: Khartoum, Sudan
          date_start: '2020-12-01'
          date_end: '2021-06-01'
          description: |2-
              * Worked as Full stack developer to provide specialized solutions in web development, systems integrations, process management systems, mobile development
              * Migrated Sudatel’s Direct Carrier Billing -a type of online payment that allows consumers to charge the cost of a purchase to their phone bill,- from Java to GoLang. This enabled more flexibility in implementing concurrent modules of the system, which resulted in a 10% increase in revenue for Sudatel’s Anghami subscription service.
              * Improved the company's internal Code Management System (CMS) web application. By using a micro-service structure (rather than the monolithic), the CMS became easier to reuse in many sites and blogs. I also add a central dashboard to monitor all of the companies applications statuses and send alerts in case of failures. The CMS is implemented in GoLang and NodeJs
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
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
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
